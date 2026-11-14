<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rzdrhw8yd"/><path class="iozeegaff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auditor-badge" /></template>
<style>
.iozeegaff {
  d: path("m9 16l2 2l4-4");
}

.rzdrhw8yd {
  d: path("m7 2.5l5 3l5-3m-7 3h4v3h-4Zm-4 3h12v13H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
