<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ii2swnbfm"/><path class="hwsrwea_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cookie-sharp" /></template>
<style>
.hwsrwea_o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 9.25h.01m-.51 5.25h.01m4.74-2.25h.01m2.74 4h.01M11 17.5h.01");
}

.ii2swnbfm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75A9.25 9.25 0 1 0 21.25 12a3 3 0 0 1-3.5-3.5a2.5 2.5 0 0 1-2.25-3A3 3 0 0 1 12 2.75Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
