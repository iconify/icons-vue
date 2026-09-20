<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGsG9qJbtn"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="e2e82nbve"/></linearGradient><linearGradient id="SVGBu3X2bSJ"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="yagxylmfe"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><g clip-path="url(#SVGqpIVPcCN)" transform="translate(2.76 1.986)scale(.11923)"><path fill="url(#SVGsG9qJbtn)" class="lzmzk1bgq"/><path fill="url(#SVGBu3X2bSJ)" class="lzmzk1bgq"/></g><path class="obrcr5v8r"/><path class="n54o3ib_j"/><path class="fk1eaksiv"/><path class="k5f14_6il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-component-html" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.e2e82nbve {
  stop-color: var(--svg-color--b13138, #b13138);
}

.fk1eaksiv {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M23.69 21.39h-2.02l-.14-1.57h2.16v-1.53h-3.84l.04.41l.38 4.22h3.42zm0 3.97h-.01l-1.7-.46l-.11-1.22h-1.53l.21 2.4l3.13.87h.01z");
}

.ho413kbqm {
  stop-color: var(--svg-color--de3641, #de3641);
}

.k5f14_6il {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.69 21.39v1.53h1.88l-.18 1.98l-1.7.46v1.59l3.13-.87l.03-.26l.35-4.02l.04-.41zm0-3.1v1.53h3.69l.03-.35l.07-.77l.04-.41z");
}

.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.n54o3ib_j {
  fill: var(--svg-color--f1662a, #f1662a);
  d: path("m23.69 28.54l4.05-1.12l.95-10.66h-5z");
}

.obrcr5v8r {
  fill: var(--svg-color--e44f26, #e44f26);
  d: path("m18.69 28.21l-1.11-12.47H29.8l-1.11 12.47l-5.01 1.39z");
}

.yagxylmfe {
  stop-color: var(--svg-color--de3641, #de3641);
  stop-opacity: 0;
}

</style>
