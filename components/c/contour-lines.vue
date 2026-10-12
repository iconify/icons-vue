<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dt3btru8e"/><path class="ihaurkc-g"/><path class="rjkltccyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contour-lines" /></template>
<style>
.dt3btru8e {
  d: path("M3.36 12c-.08-2.08.32-4.52 1.44-6s3.28-2.52 5.28-2.88s4.92-.2 6.72.72s3.52 3.12 4.08 4.8s-.04 3.52-.72 5.28s-1.84 4.12-3.36 5.28s-3.84 1.8-5.76 1.68s-4.48-.92-5.76-2.4s-1.84-4.4-1.92-6.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihaurkc-g {
  d: path("M8.16 11.52c-.16-1.44.56-3.2 1.44-4.08s2.6-1.12 3.84-1.2s2.88.08 3.6.72s.76 2.04.72 3.12s-.32 2.4-.96 3.36s-1.84 1.96-2.88 2.4s-2.4.96-3.36.24s-2.24-3.12-2.4-4.56");
}

.rjkltccyb {
  d: path("M11.76 10.56c.12-.44.72-1 1.2-1.2s1.32-.24 1.68 0s.64.96.48 1.44s-.96 1.24-1.44 1.44s-1.12.04-1.44-.24s-.6-1-.48-1.44");
}

</style>
