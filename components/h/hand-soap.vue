<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwz3nd9vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-soap" /></template>
<style>
.rwz3nd9vv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.875 10.5h1.75A4.375 4.375 0 0 1 20 14.875v2.25a4.375 4.375 0 0 1-4.375 4.375h-1.75A4.375 4.375 0 0 1 9.5 17.125v-2.25a4.375 4.375 0 0 1 4.375-4.375m.125-3h2A1.5 1.5 0 0 1 17.5 9a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 12.5 9A1.5 1.5 0 0 1 14 7.5m1 0v-4H4.5V5m0 3s-1.75 2.5-1.75 3.75a1.75 1.75 0 0 0 3.5 0C6.25 10.5 4.5 8 4.5 8");
}

</style>
