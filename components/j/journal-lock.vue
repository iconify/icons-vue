<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="brypy-cbp"/><path class="fdijoq8gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-lock" /></template>
<style>
.brypy-cbp {
  d: path("M12.2 21.5H4v-19h15v9.8M8 2.5v19");
}

.fdijoq8gv {
  d: path("M12 2.5V8l1.5-1.25L15 8V2.5m0 15h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
