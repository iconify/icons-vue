<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z-c5cpbqa"/><path class="ue_bhrbkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:install-app" /></template>
<style>
.ue_bhrbkb {
  d: path("m9 11l3 3l3-3m-4.5 7h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-c5cpbqa {
  d: path("M6 2.5h12v19H6Zm6 4V14");
}

</style>
