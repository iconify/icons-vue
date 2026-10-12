<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzmjijbyb"/><path class="hbbejybxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoe" /></template>
<style>
.hbbejybxf {
  d: path("m7.58 15.73l2.14 1.18q.52.29.1.71l-2.7 2.7q-.42.42-.71-.1l-1.18-2.14q-.29-.52.13-.94l1.28-1.28q.42-.42.94-.13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzmjijbyb {
  d: path("M21.25 2.75L10.5 13.5c-1.75.25-3.5 1.25-4.5 3");
}

</style>
