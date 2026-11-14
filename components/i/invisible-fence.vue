<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udoe70brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invisible-fence" /></template>
<style>
.udoe70brp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16V6l1.75-2.5L6 6v10m4.25-1.9V6L12 3.5L13.75 6v6.797M18 16V6l1.75-2.5L21.5 6v10M6 10h4.25m3.5 0H18m-2.5 11h.01m-3.51.5a3 3 0 0 1 3-3m-6 3a6 6 0 0 1 6-6");
}

</style>
