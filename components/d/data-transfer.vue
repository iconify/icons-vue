<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y763nobwd"/><path class="fdgmxibsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-transfer" /></template>
<style>
.fdgmxibsx {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q1.001-.001 1.933-.082m3.85-.777q.386-.14.713-.296m1.418-1.196A1 1 0 0 0 20 12m-5.5 6h7m-5.25-1.75L14.5 18l1.75 1.75m3.5-3.5L21.5 18l-1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y763nobwd {
  d: path("M13.706 21.186A23 23 0 0 1 12 21.25c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.055");
}

</style>
