<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd3_5-bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-holding-card" /></template>
<style>
.rd3_5-bgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.258 5.194l12.716-2.703l1.768 8.315l-12.716 2.703ZM2.5 17h3l3 3.5h7l5-4.5c.75-.75 0-2-1-1.5l-3.75 3H11.5M4.882 8.129l12.716-2.703");
}

</style>
