<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="d2kvgvbvc"><path class="swlu8abrm"/><path class="djnqyjb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wdio" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.djnqyjb4v {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M5.5 9v14h-.87V9zm15.31 0a7 7 0 1 1 0 14a7 7 0 0 1 0-14m-7 0L8.17 23h-.92l5.64-14zm7 .88a6.13 6.13 0 1 0 0 12.25a6.13 6.13 0 0 0 0-12.25");
}

.swlu8abrm {
  fill: var(--svg-color--ea5906, #ea5906);
  d: path("M4.19 2H27.8A2.2 2.2 0 0 1 30 4.19V27.8a2.2 2.2 0 0 1-2.19 2.2H4.2A2.2 2.2 0 0 1 2 27.8V4.2A2.2 2.2 0 0 1 4.19 2");
}

</style>
