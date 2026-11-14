<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgiglubmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bottle-refill-station" /></template>
<style>
.qgiglubmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h14.5A1.75 1.75 0 0 1 21 4.25A1.75 1.75 0 0 1 19.25 6H4.75A1.75 1.75 0 0 1 3 4.25A1.75 1.75 0 0 1 4.75 2.5m5.75 11.25v1.5L8 17.75v2.5a1.25 1.25 0 0 0 1.25 1.25h5.5A1.25 1.25 0 0 0 16 20.25v-2.5l-2.5-2.5v-1.5M12 6v2.25M12 11h.01");
}

</style>
