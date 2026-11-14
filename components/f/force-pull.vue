<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xq52442qy"/><path class="aqhhxbb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:force-pull" /></template>
<style>
.aqhhxbb6z {
  d: path("m18 9l3 3l-3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xq52442qy {
  d: path("M2.5 7h9v10h-9Zm9 5c2.25 2.5 4-2.5 6.25 0H21");
}

</style>
