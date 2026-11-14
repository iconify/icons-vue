<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hr15mo58d"/><path class="tg0y32bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-kerbside-crate" /></template>
<style>
.hr15mo58d {
  d: path("M3 4h18l-2 16H5Z");
}

.tg0y32bgf {
  d: path("M9 6.75h6v3H9ZM4.25 13h15.5M4.5 16.5h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
