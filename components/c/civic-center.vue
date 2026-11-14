<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdq4syb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:civic-center" /></template>
<style>
.tdq4syb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10a4.5 4.5 0 0 1 9 0M12 3v2.5M3.5 10h17M6 10v8m4-8v8m4-8v8m4-8v8M3 18h18M2.5 20.75h19");
}

</style>
