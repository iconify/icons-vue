<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_vrkxb-f"/><path class="qf4uhab1g"/><circle class="lv8e-1bja"/><path class="jl89vdx1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-search-sharp" /></template>
<style>
.jl89vdx1k {
  d: path("m18.75 18.75l2 2");
}

.lv8e-1bja {
  cx: 16.75px;
  cy: 16.75px;
  r: 2.75px;
}

.qf4uhab1g {
  d: path("M13.75 2.75v5.5h5.5m-11 4h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_vrkxb-f {
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

</style>
