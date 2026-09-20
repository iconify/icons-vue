<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ofs_8dbri"/><path clip-rule="evenodd" class="toi81fbcv"/><path class="ui9y2oq9f"/><g transform="translate(-4.9 -4.97)scale(.2786)" class="wkj6b4bit"><circle class="jszu2sblu"/><circle class="mf6bn0bks"/><circle class="xq0otybgo"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-quarkdown" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jszu2sblu {
  cx: 48px;
  cy: 71.99px;
  r: 3.5px;
}

.mf6bn0bks {
  cx: 51.5px;
  cy: 60.49px;
  r: 3px;
}

.ofs_8dbri {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  fill-rule: evenodd;
  d: path("M20.53 25.98a11 11 0 0 1-9.36-19.93l-.05.97a10.17 10.17 0 0 0 9.38 18.05a10 10 0 0 1 .03.9m3.7-2.73a11 11 0 0 0-7.35-18.27l.66.91a10.17 10.17 0 0 1 6.52 16.25q.1.57.17 1.11");
}

.toi81fbcv {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  fill-rule: evenodd;
  d: path("M20.83 20.02a43 43 0 0 0-1.63-5.1a35 35 0 0 0-4.81-8.9a9 9 0 0 0-2.12-2.07a2 2 0 0 0-.62-.27c-.05.06-.16.23-.26.61q-.19.66-.21 1.76q-.88.43-1.65 1c-.13-2.65.36-4.5 1.52-4.95c2.4-.92 6.75 4.55 9.71 12.22c.74 1.9 1.32 3.77 1.74 5.51a1.2 1.2 0 0 0-1.17-.19q-.31.13-.5.38m.49 2.32q.22 1.3.3 2.4q.1 1.98-.18 2.97c-.11.38-.22.55-.27.61a2 2 0 0 1-.61-.27a8 8 0 0 1-1.63-1.5a11 11 0 0 1-1.89.35c1.8 2.29 3.52 3.47 4.74 3c1.54-.6 1.9-3.69 1.18-7.86q-.2.3-.54.44a1.2 1.2 0 0 1-1.1-.14M11.6 3.67");
}

.ui9y2oq9f {
  stroke: var(--svg-color--f8f8f8, #f8f8f8);
  stroke-width: var(--svg-stroke-width--1-39px, 1.39px);
  d: path("M14.87 16.34s3.75 1.65 6.63 3.92c.16.12.4.05.45-.14c.96-3.16 2.1-6.56 2.1-6.56");
}

.wkj6b4bit {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
}

.xq0otybgo {
  cx: 56.5px;
  cy: 52.49px;
  r: 2px;
}

</style>
