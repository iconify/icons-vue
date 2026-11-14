<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vf-1jhbog"/><path class="ulgm-nb-m"/><path class="j69eh2b8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:listener-mail" /></template>
<style>
.j69eh2b8v {
  d: path("M14 18.5h2v3.25h-2Zm6 0h2v3.25h-2Z");
}

.ulgm-nb-m {
  d: path("m2.5 6.5l8.5 5l8.5-5m-4.75 15v-3.25a3.5 3.5 0 0 1 7 0v3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vf-1jhbog {
  d: path("M11.2 16H2.5V4h17v8.1");
}

</style>
