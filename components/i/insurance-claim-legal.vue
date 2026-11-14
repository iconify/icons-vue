<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fckq31b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insurance-claim-legal" /></template>
<style>
.fckq31b0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5a9.5 7 0 0 1 19 0a3.25 1.5 0 0 0-6.25 0a3.25 1.5 0 0 0-6.5 0a3.25 1.5 0 0 0-6.25 0M12 8v4.5m-3 0h5l2.5 2.5v5a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 20v-6A1.5 1.5 0 0 1 9 12.5m1.25 5h3.5");
}

</style>
