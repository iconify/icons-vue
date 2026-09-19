<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="z7g4mfbeg"/><path class="e2deuoblk"/><ellipse class="d6sp-1bzl"/><path class="quf0kxb0l"/><path class="b7aiohuta"/><path class="f9xbo7yys"/><path class="qcn40-b8b"/><path class="igg58ib1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-in-hole" /></template>
<style>
.b7aiohuta {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M45 9.3c-.9-.5-15.8-8.2-18-9.3v20.7c2.2-1.1 17.1-8.8 18-9.3c.7-.3.7-1.7 0-2.1");
}

.d6sp-1bzl {
  cx: 26.6px;
  cy: 50.3px;
  fill: var(--svg-color--c7c7c7, #c7c7c7);
  rx: 8.7px;
  ry: 3.7px;
}

.e2deuoblk {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M28 47s3-6.6 5.6-9.6h-.9S28 43.1 26 46.7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.f9xbo7yys {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M28 53.9s-.9.1-2.4.1v-7.2H28z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.igg58ib1k {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M25 52.2h2V54h-2z");
}

.qcn40-b8b {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M25 0h2v54h-2z");
}

.quf0kxb0l {
  fill: var(--svg-color--3d2905, #3d2905);
  d: path("M26.6 48.2c4.2 0 7.7 1.2 8.5 2.9c.1-.3.2-.5.2-.8c0-2-3.9-3.7-8.7-3.7s-8.7 1.6-8.7 3.7c0 .3.1.5.2.8c.9-1.6 4.3-2.9 8.5-2.9");
}

.z7g4mfbeg {
  cx: 32px;
  cy: 49.7px;
  fill: var(--svg-color--97b113, #97b113);
  rx: 30px;
  ry: 12.3px;
}

</style>
