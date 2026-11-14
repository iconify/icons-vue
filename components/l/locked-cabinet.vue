<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-1wg495k"/><path class="hvbl6frvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:locked-cabinet" /></template>
<style>
.hvbl6frvp {
  d: path("M9 12h6v4.5H9Zm1.5 0v-1.5a1.5 1.5 0 0 1 3 0V12");
}

.o-1wg495k {
  d: path("M4.5 2.5h15v19h-15Zm7.5 0v3.7m0 13.1v2.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
