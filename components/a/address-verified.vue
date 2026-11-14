<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r934w1bms"/><path class="nk-1g1b0v"/><path class="o7ukv29ko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:address-verified" /></template>
<style>
.nk-1g1b0v {
  d: path("M16 7V4h2v4.75m-4.25 9a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.o7ukv29ko {
  d: path("m15.75 17.75l1.5 1.5l2.5-2.75");
}

.r934w1bms {
  d: path("M11.56 20.5H4v-10l8-7l8 7v.84");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
