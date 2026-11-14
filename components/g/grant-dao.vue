<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh-vrjb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grant-dao" /></template>
<style>
.eh-vrjb9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.5h14.5A1.75 1.75 0 0 1 21 9.25v.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 9.75v-.5A1.75 1.75 0 0 1 4.75 7.5m2.375 4h9.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 17.875v-3.75A2.625 2.625 0 0 1 7.125 11.5M12 7.5v13m0-13c-2.5 0-5-1-5-2.75S10 3 12 7.5C14 3 17 3 17 4.75S14.5 7.5 12 7.5");
}

</style>
