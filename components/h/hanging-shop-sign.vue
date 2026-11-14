<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-7z6kn_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanging-shop-sign" /></template>
<style>
.f-7z6kn_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v18m0-15.5h17m-9.375 3h5.75a2.625 2.625 0 0 1 2.625 2.625v2.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 8.5 13.875v-2.75A2.625 2.625 0 0 1 11.125 8.5m-.625-3v3m7-3v3m-6.5 4h6");
}

</style>
