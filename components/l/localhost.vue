<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iqz-53ihh"/><path class="yc-w7nbsw"/><path class="vkrbwcb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:localhost" /></template>
<style>
.iqz-53ihh {
  d: path("M2.5 11L12 2.5l9.5 8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkrbwcb2g {
  d: path("m8 12l3 3l-3 3m5 0h3.25");
}

.yc-w7nbsw {
  d: path("M5 8.75V21.5h14V8.75");
}

</style>
