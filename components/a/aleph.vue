<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4919rkgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aleph" /></template>
<style>
.p4919rkgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 4.25l12.5 15.5M17 4.25v2C17 8.5 16 10 13.75 11M7 19.75v-2C7 15.5 8 14 10.25 13");
}

</style>
