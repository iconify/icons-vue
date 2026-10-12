<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f6z0e5bgm"/><path class="oq-y3cbpd"/><path class="hj5fjpn0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lab-scale-sharp" /></template>
<style>
.f6z0e5bgm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h18.5v8H2.75zm3.5 4h4.5");
}

.hj5fjpn0o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.5h11.5M12 9.5v3.75M9.25 2.75h5.5V7h-5.5z");
}

.oq-y3cbpd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 17.25h.01m2.74 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
