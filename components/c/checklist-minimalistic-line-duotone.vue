<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxnzn9nmw"/><path class="w2dqczb0r"/><path class="zs9521pzc"/><path class="er-qpx8gd"/><path class="lffdqhb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checklist-minimalistic-line-duotone" /></template>
<style>
.er-qpx8gd {
  d: path("M13 9L18 9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lffdqhb9f {
  d: path("M13 16L18 16");
}

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w2dqczb0r {
  stroke-linejoin: round;
  d: path("M6 15.8L7.14286 17L10 14");
}

.zs9521pzc {
  stroke-linejoin: round;
  d: path("M6 8.8L7.14286 10L10 7");
}

</style>
