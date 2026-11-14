<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi34kcbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-cleaning" /></template>
<style>
.zi34kcbwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.821 14.5H5.5L3 5.5h2l3 4h9.4m1.25.096c1.803.315 2.85 1.36 2.85 2.404c0 .538-.278 1.076-.794 1.515M13.5 14.5l-.86 1.105m-2.148 2.763L10 19m8-4.5l1 2l2 1l-2 1l-1 2l-1-2l-2-1l2-1Z");
}

</style>
