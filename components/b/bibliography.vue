<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwgr5e0se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bibliography" /></template>
<style>
.zwgr5e0se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.5h14a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 17A2.5 2.5 0 0 1 5 14.5m2-5h10a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 12A2.5 2.5 0 0 1 7 9.5m-1-5h8A2.5 2.5 0 0 1 16.5 7A2.5 2.5 0 0 1 14 9.5H6A2.5 2.5 0 0 1 3.5 7A2.5 2.5 0 0 1 6 4.5m12.5 10v5m-11-10v5m5.5-10v5");
}

</style>
