<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="raw09pb_u"/><path class="ve84-8o-u"/><path class="totlwmxka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-image-sharp" /></template>
<style>
.raw09pb_u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v11.45H2.75v-2.5Zm0 3.5h18.5");
}

.totlwmxka {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 13.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ve84-8o-u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 17.25l3-3.25l2.5 2.5l1.5-1.5l2 2.25");
}

</style>
