<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v-6_70w2a"/><circle class="j_mfn8vtz"/><path class="xaho99ahr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:certificate-sharp" /></template>
<style>
.j_mfn8vtz {
  cx: 16.5px;
  cy: 16.25px;
  r: 3px;
}

.v-6_70w2a {
  d: path("M21.25 13.48V3.75H2.75v13.5h8.34a5.5 5.5 0 0 1 10.16-3.77ZM6.5 7.75h11m-11 3.75H11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xaho99ahr {
  d: path("M15 18.85v2.4l1.5-1l1.5 1v-2.4");
}

</style>
