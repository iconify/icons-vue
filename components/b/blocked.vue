<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf3s4bc_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blocked" /></template>
<style>
.rf3s4bc_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.731 2.992l5.277 5.277v7.462l-5.277 5.277H8.269l-5.277-5.277V8.269l5.277-5.277ZM7 7l10 10");
}

</style>
