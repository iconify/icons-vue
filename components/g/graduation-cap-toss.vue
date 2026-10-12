<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="au1frl24o"/><path class="csq8_ef7k"/><path class="cxj77wb9c"/><path class="gja2f-h1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graduation-cap-toss" /></template>
<style>
.au1frl24o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.96 8.83l6.25-4.98q.59-.47 1.32-.28l7.74 2.01q.73.19.14.66l-6.25 4.98q-.59.47-1.32.28L4.1 9.49q-.73-.19-.14-.66");
}

.csq8_ef7k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 10.52l.71 3.33c.26 1.22 2.42 1.78 4.87 1.26c2.44-.52 4.19-1.91 3.93-3.13l-.7-3.33m2.98-2.78v5");
}

.cxj77wb9c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.51 11.37h.01");
}

.gja2f-h1b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13.75q.375 2.625 3 3.75m-.75 2.75c1.5.75 3.25.75 4.75.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
