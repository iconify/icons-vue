<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnzceqa9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-needle" /></template>
<style>
.tnzceqa9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.575 16.596l5.657-5.657l2.829 2.829l-5.657 5.657Zm7.071-4.242l7.779-7.779M7.404 13.768l2.828 2.828");
}

</style>
