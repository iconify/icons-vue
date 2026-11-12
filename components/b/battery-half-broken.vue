<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="na80fjbih"/><path class="by8lpqc5r"/><path class="cxn0dz0cz"/><path class="d7egxzbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-half-broken" /></template>
<style>
.by8lpqc5r {
  d: path("M10.5 9C10.5 9 11 9.9 11 12C11 14.1 10.5 15 10.5 15");
}

.cxn0dz0cz {
  d: path("M20 10V14C20.9428 14 21.4142 14 21.7071 13.7071C22 13.4142 22 12.9428 22 12C22 11.0572 22 10.5858 21.7071 10.2929C21.4142 10 20.9428 10 20 10Z");
}

.d7egxzbrr {
  d: path("M2 12C2 8.22876 2 6.34315 3.17157 5.17157C4.34315 4 6.22876 4 10 4H11.5C15.2712 4 17.1569 4 18.3284 5.17157C19.5 6.34315 19.5 8.22876 19.5 12C19.5 15.7712 19.5 17.6569 18.3284 18.8284C17.1569 20 15.2712 20 11.5 20H10C6.22876 20 4.34315 20 3.17157 18.8284C2.51839 18.1752 2.22937 17.3001 2.10149 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na80fjbih {
  d: path("M7 9C7 9 7.5 9.9 7.5 12C7.5 14.1 7 15 7 15");
}

</style>
