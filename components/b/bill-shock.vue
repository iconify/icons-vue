<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uia2ecb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bill-shock" /></template>
<style>
.uia2ecb5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 18.15V20l-3.5-1.75l-3.75 2V3h14v9.1m-3.85.15h-2.9v4.6M8.5 6.5h7m-7 3h7M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
