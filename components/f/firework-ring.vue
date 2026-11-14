<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlc29xisk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firework-ring" /></template>
<style>
.xlc29xisk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8V2.5M12 16v5.5M8 12H2.5M16 12h5.5m-6.75-2.75L16.5 7.5M9.25 9.25L7.5 7.5m7.25 7.25l1.75 1.75m-7.25-1.75L7.5 16.5M18.75 5.25h.01m-13.51 0h.01m13.49 13.5h.01m-13.51 0h.01");
}

</style>
