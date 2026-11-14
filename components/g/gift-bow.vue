<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvhofyb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-bow" /></template>
<style>
.lvhofyb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13c-4-6-9-5-8-2s5 3 8 2m0 0c4-6 9-5 8-2s-5 3-8 2m0 0l-3 7.5m3-7.5l3 7.5");
}

</style>
