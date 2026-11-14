<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0jewabsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crossfader" /></template>
<style>
.s0jewabsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.125 7h3.75A2.625 2.625 0 0 1 16.5 9.625v4.75A2.625 2.625 0 0 1 13.875 17h-3.75A2.625 2.625 0 0 1 7.5 14.375v-4.75A2.625 2.625 0 0 1 10.125 7M2.5 12h5m9 0h5M12 9.75v4.5M2.5 9.5v5m19-5v5");
}

</style>
