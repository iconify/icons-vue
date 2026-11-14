<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1febfj8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-reception" /></template>
<style>
.j1febfj8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 12.75h12.75A2.625 2.625 0 0 1 21 15.375v3.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.625v-3.25a2.625 2.625 0 0 1 2.625-2.625M7 10a5 5 0 0 1 10 0M5.5 10h13M12 3v2");
}

</style>
