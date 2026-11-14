<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwbytnbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bus-station" /></template>
<style>
.bwbytnbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7H10M3.5 7v13.5M9 7v13.5m-5.5-4H9M12 6h9.5v12.5H12Zm0 5h9.5m-7.25 4.25h.01m4.99 0h.01M14 18.5v2m5.5-2v2");
}

</style>
