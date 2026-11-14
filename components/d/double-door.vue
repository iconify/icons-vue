<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6t-hvbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:double-door" /></template>
<style>
.e6t-hvbqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5v-17a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v17m-17.5 0h19M12 2.5v19m-2.75-11v3m5.5-3v3");
}

</style>
