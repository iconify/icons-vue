<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wotj1kbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dairy-fridge" /></template>
<style>
.wotj1kbnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.417 21.5H4V9l3-4.5v-2h8.5v2l3 4.5v3.483M4 9h14.5m0 6.25v6.5M15.75 17l5.5 3m-5.5 0l5.5-3");
}

</style>
