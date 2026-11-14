<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glsfx2bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beat-maker-plus" /></template>
<style>
.glsfx2bth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 18.5H2.5v-16h16v9.7m-12-5.7h.01m3.99 0h.01m3.99 0h.01m-8.01 4h.01m3.99 0h.01m3.99 0h.01m-8.01 4h.01m3.99 0h.01m3.99 0h.01M18 15v6m-3-3h6");
}

</style>
