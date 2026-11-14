<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gc1plirtt"/><path class="uuywaq6-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:affordability-check" /></template>
<style>
.gc1plirtt {
  d: path("M11.4 20H2.5V5h19v9m-19-4h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuywaq6-y {
  d: path("M16.9 11.75h-.4v-3.5h5v3.5h-2.4M18.5 10h.01m-4.26 8L18 14.5l3.75 3.5v3.75h-7.5Z");
}

</style>
