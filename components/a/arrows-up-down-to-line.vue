<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0cjpe1if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrows-up-down-to-line" /></template>
<style>
.p0cjpe1if {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6.25M9 5.5l3 3.25l3-3.25m-3 16v-6.25M9 18.5l3-3.25l3 3.25M4 12h16");
}

</style>
