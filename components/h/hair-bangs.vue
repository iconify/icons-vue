<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trxeadcsa"/><path class="jiy4mehfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-bangs" /></template>
<style>
.jiy4mehfh {
  d: path("M8 9.5v4a4 4 0 0 0 8 0v-4");
}

.trxeadcsa {
  d: path("M4.5 21V10a7.5 7.5 0 0 1 15 0v11M4.5 9.5h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
