<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p--ib1bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-cleaning" /></template>
<style>
.p--ib1bgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.821 14.5H5.5L3 5.5h2l3 4h9.5c2.5 0 4 1.25 4 2.5c0 .569-.311 1.138-.885 1.589M13.5 14.5L10 19m8.5-3.5l.276.553a1.5 1.5 0 0 0 .671.671L20 17a.559.559 0 0 1 0 1l-.553.276a1.5 1.5 0 0 0-.671.671l-.276.553a.559.559 0 0 1-1 0l-.276-.553a1.5 1.5 0 0 0-.671-.671L16 18a.559.559 0 0 1 0-1l.553-.276a1.5 1.5 0 0 0 .671-.671l.276-.553a.559.559 0 0 1 1 0");
}

</style>
