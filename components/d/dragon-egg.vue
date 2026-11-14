<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dv9y59b4v"/><path class="ma2lg85kg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dragon-egg" /></template>
<style>
.dv9y59b4v {
  d: path("M12 2.5c4.5 0 7 6.5 7 11.5c0 4.5-3 7.5-7 7.5s-7-3-7-7.5C5 9 7.5 2.5 12 2.5Z");
}

.ma2lg85kg {
  d: path("m5.25 12.5l2.75-2l2.5 3l3-3l2.5 3l2.75-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
