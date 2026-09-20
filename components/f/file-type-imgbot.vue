<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="al7hjwl7p"/><path class="q758ihbbs"/><circle class="sb2as733r"/><path class="p-f69v8fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-imgbot" /></template>
<style>
.al7hjwl7p {
  width: 17.76px;
  height: 12.45px;
  x: 7.12px;
  y: 10.97px;
  fill: none;
  stroke: var(--svg-color--438977, #438977);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  rx: 0.48px;
}

.p-f69v8fk {
  fill: var(--svg-color--438977, #438977);
  d: path("m20.97 2.73l-1 5.75h2.01zM12.1 29.9v-3.85a.1.1 0 0 1 .14-.08L19.76 30a.1.1 0 0 0 .15-.09v-3.85a.1.1 0 0 0-.15-.08L12.24 30a.1.1 0 0 1-.14-.09");
}

.q758ihbbs {
  fill: none;
  stroke: var(--svg-color--438977, #438977);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-83px, 0.83px);
  d: path("M10.05 18.07c0-1.18.91-2.14 2.04-2.14s2.05.96 2.05 2.14m3.72 0c0-1.18.92-2.14 2.05-2.14s2.04.96 2.04 2.14");
}

.sb2as733r {
  cx: 20.94px;
  cy: 3.42px;
  r: 1.41px;
  fill: var(--svg-color--438977, #438977);
}

</style>
