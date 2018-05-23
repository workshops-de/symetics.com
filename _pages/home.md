---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Symetics
layout: page
permalink: /
---

<div class="container text-center wallpaper-front container-with-margin">
  <p class="page-title">
    Wir sind Symetics.<br><br>
    <em style="font-size: 0.8em;">
      Wir nutzen das Web als Plattform für moderne Anwendungen.<br>
      Und helfen Ihnen dabei, dasselbe zu tun.
    </em>
  </p>
</div>

<br>



<div class="container container-with-margin">
  <div class="row">
    <div class="col-md-8 col-md-offset-2">
      <h2 class="section-title text-center">
        Wir beraten, schulen und entwickeln.
      </h2>

      <p class="text-justify">
        Unser Team besteht aus Spezialisten, die seit mehr als einer Dekade Anwendungen für das Web erstellen. Im
        Bereich der Single-Page-Apps setzen wir vorzugsweise auf
        <a href="https://angularjs.org/" target="_blank">Angular</a> und gelten auf diesem Gebiet als anerkannte
        Experten.
      </p>

      <h3>Aufschlussreiche Workshops &amp; Schulungen</h3>

      <p class="text-justify">
        Unsere Erfahrungen geben wir weiter, damit Ihr Team nicht die Fehler macht, die wir bereits gemacht haben.
        Darüber hinaus können Sie unseren monatlichen
        <a href="https://angularjs.de/workshops/angular-intensiv">Intensiv-Workshop</a>
        besuchen oder eine speziell auf Ihr Projekt zugeschnittene
        <a href="https://angularjs.de/inhouse-workshop?course=Angular+%26+TypeScript+Intensiv-Workshop+%283+Tage%29">Inhouse-Schulung</a> anfordern.
      </p>

    </div>
  </div>
</div>



<div class="box box-info box-with-background-logo">
  <div class="container container-with-margin">
    <div class="row">
      <div class="col-lg-3 col-lg-offset-2">
        <%= image_tag 'project-workshops.png', class: 'img-responsive' %>
      </div>
      <div class="col-lg-5 col-lg-offset-0">
        <p>

        <h2>Workshops.DE</h2>
        </p>
        <p class="text-justify">
          Seit 2017 betreiben wir Workshops.DE, ein Lernportal mit Schulungen zu Themen wie Angular, React, Docker, Java und vieles mehr.
          Die Besonderheit hierbei ist unser Lern-System, mit dem wir den Lernerfolg unserer Teilnehmern noch weiter steigern können.
        </p>

        <p>
          <%= link_to "Workshops.DE #{icon 'arrow-right'}", 'https://workshops.de', target: '_blank', class: 'btn btn-default btn-text-black text-uppercase btn-with-margin' %>
        </p>
      </div>
    </div>
  </div>
</div>

<div class="container container-with-margin">
  <div class="row">
    <div class="col-md-8 col-md-offset-2">
      <h3>Professionelle Beratung</h3>

      <p class="text-justify">
        Wir helfen Ihnen zu entscheiden, ob Angular das richtige Framework für Ihr Projekt ist. Wir haben in den
        vergangenen zwei Jahren an mehreren Großprojekten mitgearbeitet und wissen, wo die Grenzen des Frameworks
        liegen. Unsere Erfahrungen helfen Ihnen, die teuersten Fehler zu vermeiden und stattdessen reibungslos zu
        starten.
      </p>


    </div>
  </div>
</div>


<div class="container container-with-margin">
  <div class="row">
    <div class="col-md-8 col-md-offset-2">
      <h3>Wegweisende Entwicklung</h3>

      <p class="text-justify">
        Wir unterstützen Sie gerne mit unserem Expertenwissen bei der Umsetzung Ihrer Angular-Applikation. Alternativ
        können Sie die Entwicklung auch vollständig uns überlassen. Am besten sind wir dazu von Anfang an dabei, um eine
        solide Grundlage für Ihr nächstes Projekt zu schaffen.
      </p>
    </div>
  </div>

</div>




<div class="box box-primary box-with-background-logo">
  <div class="container container-with-margin">
    <div class="row">
      <div class="col-lg-3 col-lg-offset-2">
        <%= image_tag 'project-angularjs.png', class: 'img-responsive' %>
      </div>
      <div class="col-lg-5 col-lg-offset-0">
        <p>

        <h2>AngularJS.DE</h2>
        </p>
        <p class="text-justify">
          Seit 2013 betreiben wir AngularJS.DE, das größte deutsche Portal zum Framework. Die Community-Plattform bietet
          viele hochwertige Artikel zum Thema Angular sowie ein Einsteiger-Tutorial und eine Entwicklerbörse.
        </p>

        <p>
          <%= link_to "AngularJS.DE #{icon 'arrow-right'}", 'https://angularjs.de', target: '_blank', class: 'btn btn-default btn-text-black text-uppercase btn-with-margin' %>
        </p>
      </div>
    </div>
  </div>
</div>

{% include _references.html %}