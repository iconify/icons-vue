<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp76u5b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:butler-sink" /></template>
<style>
.wp76u5b6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 11h12.75A2.625 2.625 0 0 1 21 13.625v4.75A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-4.75A2.625 2.625 0 0 1 5.625 11M3 14h18M7.5 11V7.5h9V11M12 7.5v-3a2 2 0 0 1 4 0");
}

</style>
