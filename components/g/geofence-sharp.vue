<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xd179tpla"/><path class="a4sqm4byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:geofence-sharp" /></template>
<style>
.a4sqm4byg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xd179tpla {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.88 3.66l.97-.42L12 2.75l1.09.62l1.98 1.14m2.61 1.48l1.98 1.14l1.09.62l-.15 1.24l-.29 2.4m-.37 2.97l-.29 2.4L19.5 18l-1.19.37l-2.63.81m-2.86.89l-2.63.81l-1.19.37l-.74-1l-1.24-1.67m-1.79-2.41L3.99 14.5l-.74-1l.28-1.22l.26-1.19m.67-2.93l.26-1.19L5 5.75l1.15-.49l.97-.42M12 16.5h-.314l-.236-.22c-1.7-1.68-3.2-3.38-3.2-5.28a3.75 3.75 0 0 1 7.5 0c0 1.9-1.5 3.6-3.2 5.28l-.236.22z");
}

</style>
