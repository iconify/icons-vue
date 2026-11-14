<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr_5efb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frost-protection" /></template>
<style>
.sr_5efb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l7.5 2.75V11c0 5-3.25 8.75-7.5 10.5C7.75 19.75 4.5 16 4.5 11V5.25ZM12 7v9M8.25 9.25l7.5 4.5m-7.5 0l7.5-4.5");
}

</style>
