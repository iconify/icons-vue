<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xpclw3b8l"/><path class="x5dxxmqqz"/><path class="bo6p11gje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fabric-dyeing-vat" /></template>
<style>
.bo6p11gje {
  d: path("M12.5 13.25V5.5A2.5 2.5 0 0 1 15 3h2.5A2.5 2.5 0 0 1 20 5.5V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5dxxmqqz {
  d: path("M4.5 13q3-1.5 6 0t6 0");
}

.xpclw3b8l {
  d: path("M3 7h1.5v12.5A1.5 1.5 0 0 0 6 21h9a1.5 1.5 0 0 0 1.5-1.5V7");
}

</style>
