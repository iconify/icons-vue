<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ws6yb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-fence" /></template>
<style>
.s7ws6yb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V7.5L4.75 5L6.5 7.5V21Zm7.25 0V5.5L12 3l1.75 2.5V21Zm7.25 0V7.5L19.25 5L21 7.5V21Zm-11-11h3.75m3.5 0h3.75m-11 6.5h3.75m3.5 0h3.75");
}

</style>
