<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdxi9v3mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-lane" /></template>
<style>
.wdxi9v3mv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 14.5h13.5a2.75 2.75 0 0 1 2.75 2.75A2.75 2.75 0 0 1 18.75 20H5.25a2.75 2.75 0 0 1-2.75-2.75a2.75 2.75 0 0 1 2.75-2.75m-.5-11h3A1.75 1.75 0 0 1 9.5 5.25v1.5A1.75 1.75 0 0 1 7.75 8.5h-3A1.75 1.75 0 0 1 3 6.75v-1.5A1.75 1.75 0 0 1 4.75 3.5m1.5 5v6m8.5-6h2.5A1.75 1.75 0 0 1 19 10.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 13 12.75v-2.5a1.75 1.75 0 0 1 1.75-1.75M7 17.25h.01m4.99 0h.01m4.99 0h.01");
}

</style>
