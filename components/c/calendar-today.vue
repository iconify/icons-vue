<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr8m1_bim"/><path class="b94i40l_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-today" /></template>
<style>
.b94i40l_y {
  fill: currentColor;
  d: path("M10 15.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.fr8m1_bim {
  d: path("M3 4.5h18V21H3Zm0 5h18m-13-7v4m8-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
