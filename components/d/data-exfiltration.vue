<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c4qr3tbhi"/><path class="a5emuwbmb"/><path class="vw4q_gb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-exfiltration" /></template>
<style>
.a5emuwbmb {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.885 0 1.716-.065");
}

.c4qr3tbhi {
  d: path("M11.334 21.24C7.242 21.122 4 19.924 4 18.5v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.555");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vw4q_gb0s {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5M15 21l6-6m-4.5 0H21v4.5");
}

</style>
