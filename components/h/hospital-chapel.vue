<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgecfrs2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-chapel" /></template>
<style>
.zgecfrs2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 11h3.5a1.75 1.75 0 0 1 1.75 1.75v7a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-7A1.75 1.75 0 0 1 10.25 11M12 2.5c1.75 2 2.5 3.25 2.5 4.5c0 1.4-1.1 2.25-2.5 2.25S9.5 8.4 9.5 7c0-1.25.75-2.5 2.5-4.5m0 6.75V11M5 21.5h14");
}

</style>
