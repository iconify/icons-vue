<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sgahzcm7h"/><path class="z4gavt2hv"/><circle class="q1fvssb8e"/><path class="vag9hybes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-stash-sharp" /></template>
<style>
.q1fvssb8e {
  cx: 12px;
  cy: 6.5px;
  r: 2.25px;
}

.sgahzcm7h {
  d: path("M3.75 12.75h16.5v8.5H3.75z");
}

.vag9hybes {
  d: path("M12 2.75v1.5m0 4.5v2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4gavt2hv {
  d: path("M3.75 16h4.5l1.25 1.75h5L15.75 16h4.5");
}

</style>
