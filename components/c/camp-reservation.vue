<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ze49ik-av"/><path class="wc3iedi8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-reservation" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc3iedi8f {
  d: path("M6.5 18.75L12 12l5.5 6.75M12 12l-2 6.75");
}

.ze49ik-av {
  d: path("M3 4.5h18v17H3Zm5-2v4m8-4v4M3 9h18");
}

</style>
