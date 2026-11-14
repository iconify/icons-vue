<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6bnxb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:line-height-tight" /></template>
<style>
.qq6bnxb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h17m-17 4h17M12 2.5v4M9.75 4.25L12 6.5l2.25-2.25M12 21.5v-4m-2.25 2.25L12 17.5l2.25 2.25");
}

</style>
