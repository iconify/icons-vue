<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ens4qpg9v"/><path class="o1zlll-zk"/><path class="horrqsboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:external-drive-sharp" /></template>
<style>
.ens4qpg9v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5v14H5.75zm3.5 3.75h5.5");
}

.horrqsboc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.75v4.5h7.25");
}

.o1zlll-zk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
