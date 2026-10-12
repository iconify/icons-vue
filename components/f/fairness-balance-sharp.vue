<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efzlufb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fairness-balance-sharp" /></template>
<style>
.efzlufb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25v17.5m-4 0h8M6 6h12M3.5 13.25L6 6l2.5 7.25m7 0L18 6l2.5 7.25m-17.5 0h6a3 2.5 0 0 1-6 0Zm12 0h6a3 2.5 0 0 1-6 0Z");
}

</style>
