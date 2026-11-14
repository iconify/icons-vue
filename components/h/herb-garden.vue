<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg9jhviza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:herb-garden" /></template>
<style>
.tg9jhviza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M12 20V9m0 0c0-3 2-5 5-5c0 3-2 5-5 5M6.5 20v-6m0 0c0-2.5-2-4-4-4c0 2.5 2 4 4 4m11 6v-6m0 0c0-2.5 2-4 4-4c0 2.5-2 4-4 4");
}

</style>
