<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwevkibxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ambient-lighting" /></template>
<style>
.mwevkibxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5V11l6.5-7.5H19a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2Zm3-3h12m-10-3l-1.25-2.75M12 14.5v-3.25m4 3.25l1.25-2.75");
}

</style>
