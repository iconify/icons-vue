<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kstoa4xmg"/><path class="gqg6zkbme"/><path class="pstn25chr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-shuffle" /></template>
<style>
.gqg6zkbme {
  d: path("M3.5 17H8c5 0 3-10 8-10h3m-2 8l2.5 2l-2.5 2");
}

.kstoa4xmg {
  d: path("M3.5 7H8c5 0 3 10 8 10h3");
}

.pstn25chr {
  d: path("m17 5l2.5 2L17 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
