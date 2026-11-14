<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hf0dphj5v"/><path class="qhhkkib1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-missing" /></template>
<style>
.hf0dphj5v {
  d: path("M4.5 9V5A2.5 2.5 0 0 1 7 2.5h3m3.5 0l5 5V11");
}

.qhhkkib1i {
  d: path("M13.5 2.5v3a2 2 0 0 0 2 2h3m-14 6V19A2.5 2.5 0 0 0 7 21.5h4m7-7V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
