<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw0zyeplh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gs1-barcode" /></template>
<style>
.rw0zyeplh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5h10a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 17 19H7a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 7 5m1 4v6m2.5-6v6M12 9v6m2.5-6v6M16 9v6m-9 1.5h10");
}

</style>
