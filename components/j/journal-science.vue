<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w75lnl3mr"/><path class="t8d4evw3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-science" /></template>
<style>
.t8d4evw3w {
  d: path("M5.5 5.5v-3h12V12m-12-3H10m6.75 6v2l-2 4.5h6.5l-2-4.5v-2M16 15h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w75lnl3mr {
  d: path("M2.5 5.5H13v13H2.5Z");
}

</style>
