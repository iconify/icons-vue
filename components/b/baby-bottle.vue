<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im-1machu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-bottle" /></template>
<style>
.im-1machu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6V3.5a1.5 1.5 0 0 1 3 0V6m-5 0h7v3h-7Zm-1 3h9v12h-9Zm2.5 4h2.5M10 16.5h2.5");
}

</style>
