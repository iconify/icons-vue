<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhc5bkbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-garden" /></template>
<style>
.bhc5bkbfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 15h15.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 4.25 15M2.5 18.25h19M5.5 15v-5m0 2C4 12 3.25 11 3.25 9.75c1.25 0 2.25.75 2.25 2.25m0-1.5C5.5 9 6.25 8 7.75 8c0 1.5-.75 2.5-2.25 2.5M12 15V9m0 2c-1.5 0-2.25-1-2.25-2.25C11 8.75 12 9.5 12 11m0-1.5C12 8 12.75 7 14.25 7c0 1.5-.75 2.5-2.25 2.5m6.5 5.5v-5m0 2c-1.5 0-2.25-1-2.25-2.25c1.25 0 2.25.75 2.25 2.25m0-1.5c0-1.5.75-2.5 2.25-2.5c0 1.5-.75 2.5-2.25 2.5");
}

</style>
