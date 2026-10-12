<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mivukbcci"/><circle class="q37snoy7l"/><circle class="s33wmo_6g"/><path class="n3o3-wbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cardboard-vr-sharp" /></template>
<style>
.mivukbcci {
  d: path("M4.25 7.5h17V19H15l-1.25-4L12 13.25L10.25 15L9 19H2.75V7.5z");
}

.n3o3-wbtf {
  d: path("M7 3.5h10v4H7z");
}

.q37snoy7l {
  cx: 7.5px;
  cy: 11.75px;
  r: 1.75px;
}

.s33wmo_6g {
  cx: 16.5px;
  cy: 11.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
