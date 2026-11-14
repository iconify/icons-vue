<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="whl9nbc_l"/><path class="qlvirmb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bubble-tea-sealed" /></template>
<style>
.qlvirmb1l {
  d: path("M11.5 2.5h3v8h-3Zm-2 16.25h.01m4.99 0h.01M12 15.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whl9nbc_l {
  d: path("m5.5 7.5l1.5 14h10l1.5-14M4 7.5h16");
}

</style>
