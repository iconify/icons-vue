<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dr2shmbul"/><path class="p8a8swx0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drinks-cooler" /></template>
<style>
.dr2shmbul {
  d: path("M3.5 2.5h17v19h-17Zm0 3.5h17m-17 7.5h13M3.5 20h13");
}

.p8a8swx0j {
  d: path("M6 13.5V11c0-.75.75-1.25.75-1.75V8h1.5v1.25c0 .5.75 1 .75 1.75v2.5m2 0V11c0-.75.75-1.25.75-1.75V8h1.5v1.25c0 .5.75 1 .75 1.75v2.5M6 20v-2.5c0-.75.75-1.25.75-1.75V14.5M9 20v-2.5c0-.75-.75-1.25-.75-1.75V14.5M11 20v-2.5c0-.75.75-1.25.75-1.75V14.5M14 20v-2.5c0-.75-.75-1.25-.75-1.75V14.5M18.5 9v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
