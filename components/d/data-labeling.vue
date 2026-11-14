<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cq2mflbmn"/><path class="jujxzbcuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-labeling" /></template>
<style>
.cq2mflbmn {
  d: path("M11.2 17.5H2.5v-14h17v8.3");
}

.jujxzbcuv {
  d: path("m2.5 14.5l5-5l3.697 3.697M12.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14 14.5h4.25l3.5 3.5l-3.5 3.5H14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
