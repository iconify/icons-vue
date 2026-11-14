<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhb4cqblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cattle-grid" /></template>
<style>
.xhb4cqblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 2.5l-4.75 19M16 2.5l4.75 19m-14.5-12h11.5m-12.25 3h13m-13.75 3h14.5M12 2.5v4m0 12v3");
}

</style>
