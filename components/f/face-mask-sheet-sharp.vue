<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7pnjvb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-mask-sheet-sharp" /></template>
<style>
.t7pnjvb7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c4.5 0 7.25 3.5 7.25 8.5c0 6-3.5 10-7.25 10s-7.25-4-7.25-10c0-5 2.75-8.5 7.25-8.5ZM7.75 10.5h2.75m3 0h2.75m-6.25 6h4");
}

</style>
