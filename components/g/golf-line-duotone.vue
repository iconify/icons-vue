<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><ellipse class="f2jbpwb_z"/><path class="ya4v2ogmm"/><path class="hzret1bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-line-duotone" /></template>
<style>
.f2jbpwb_z {
  cx: 12px;
  cy: 18.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 10px;
  ry: 3.5px;
}

.hzret1bgp {
  d: path("M12 3.5L17.4224 6.21114C18.9835 6.99169 19.764 7.38196 19.764 8C19.764 8.61804 18.9835 9.00831 17.4224 9.78886L12 12.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya4v2ogmm {
  d: path("M12 18V2");
}

</style>
