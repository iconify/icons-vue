<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGsG9qJbtn"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="e2e82nbve"/></linearGradient><linearGradient id="SVGBu3X2bSJ"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="yagxylmfe"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><g clip-path="url(#SVGqpIVPcCN)" transform="translate(2.76 1.986)scale(.11923)"><path fill="url(#SVGsG9qJbtn)" class="lzmzk1bgq"/><path fill="url(#SVGBu3X2bSJ)" class="lzmzk1bgq"/></g><path class="f82dshb-y"/><path class="khha88boi"/><path class="yrz7khooq"/><path class="c-ph7zbxh"/><path class="cy0h4cf2u"/><path class="j_8ynpahf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-component-css" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.c-ph7zbxh {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("m23.65 25.35l-1.72-.47l-.11-1.23h-1.56l.22 2.43l3.16.88l.01-.01z");
}

.cy0h4cf2u {
  fill: var(--svg-color--fff, #fff);
  d: path("m25.56 22.81l-.19 2.07l-1.72.47v1.61l3.17-.88l.02-.26l.27-3.01z");
}

.e2e82nbve {
  stop-color: var(--svg-color--b13138, #b13138);
}

.f82dshb-y {
  fill: var(--svg-color--1572b6, #1572b6);
  d: path("m18.59 28.34l-1.12-12.6h12.35l-1.13 12.6l-5.05 1.4z");
}

.ho413kbqm {
  stop-color: var(--svg-color--de3641, #de3641);
}

.j_8ynpahf {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M23.65 18.2v1.55h-3.73l-.03-.35l-.08-.78l-.03-.42zm-.01 3.13v1.55h-1.7l-.03-.35l-.07-.78l-.03-.42z");
}

.khha88boi {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("m23.64 28.67l4.09-1.14l.96-10.76h-5.05z");
}

.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.yagxylmfe {
  stop-color: var(--svg-color--de3641, #de3641);
  stop-opacity: 0;
}

.yrz7khooq {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.64 21.33h2.05l.14-1.58h-2.19V18.2h3.88l-.04.42l-.38 4.26h-3.46z");
}

</style>
