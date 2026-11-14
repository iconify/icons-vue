<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf-xg_b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:burnout" /></template>
<style>
.gf-xg_b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3s4.5 4.5 4.5 9.75a4.5 4.5 0 0 1-9 0C7.5 10.5 9 9 10 7.5c.5 1.75 1.25 2.25 2 2.25C12.5 7.5 12 5 12 3ZM5 21h14");
}

</style>
