<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3mnfccii"/><path class="zggda-2nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:innings-scoreboard" /></template>
<style>
.n3mnfccii {
  d: path("M2.5 3.5h19v13h-19Zm4.5 13V21m10-4.5V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zggda-2nd {
  d: path("M6 10a2 3 0 1 0 4 0a2 3 0 1 0-4 0Zm8 0a2 3 0 1 0 4 0a2 3 0 1 0-4 0Z");
}

</style>
