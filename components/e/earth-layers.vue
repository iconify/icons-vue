<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="agbwxyu4b"/><path class="og913g3xv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-layers" /></template>
<style>
.agbwxyu4b {
  d: path("M12 12V2.5a9.5 9.5 0 1 0 9.5 9.5Z");
}

.og913g3xv {
  d: path("M12 8.5a3.5 3.5 0 0 1 3.5 3.5M12 5.5a6.5 6.5 0 0 1 6.5 6.5M12 2.5a4.5 9.5 0 0 0 0 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
