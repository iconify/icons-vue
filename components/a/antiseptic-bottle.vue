<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l5mguzt3c"/><path class="wxffg7clw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antiseptic-bottle" /></template>
<style>
.l5mguzt3c {
  d: path("m5 12.5l3.5-3h7l3.5 3V20a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20Zm4-9h6v6H9ZM9 6h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxffg7clw {
  d: path("M12 12.25s2.75 2.75 2.75 4a2.75 2.75 0 0 1-5.5 0c0-1.25 2.75-4 2.75-4Z");
}

</style>
