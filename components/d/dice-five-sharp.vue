<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xwa9a1rqc"/><path class="mindnib1o"/><path class="kqif8_bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dice-five-sharp" /></template>
<style>
.kqif8_bws {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.5h.01m2.29 5.9h.01m3.29 1.8h.01m-9.51-.95h.01m2.09 3.65h.01m-.01-4.86h.01M6 15.46h.01M6 10.6h.01");
}

.mindnib1o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.8L12 12l7.25-4.2M12 12v8.4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xwa9a1rqc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.3 3.75l5.19 3l1.3.75v9l-1.3.75l-5.19 3L12 21l-1.3-.75l-5.19-3l-1.3-.75v-9l1.3-.75l5.19-3L12 3z");
}

</style>
