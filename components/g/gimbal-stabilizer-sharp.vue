<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ayv-53bwz"/><path class="su7wuov-l"/><path class="vxh593bgm"/><circle class="eav5g_b0l"/><circle class="y9y1r0c9o"/><path class="z9yu7jb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gimbal-stabilizer-sharp" /></template>
<style>
.ayv-53bwz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75h13.5v5H7.75z");
}

.eav5g_b0l {
  cx: 4.5px;
  cy: 5.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.su7wuov-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vxh593bgm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 11.5h-6V6.75M6 5.25h1.75");
}

.y9y1r0c9o {
  cx: 12px;
  cy: 11.5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9yu7jb1w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 14h4v7.25h-4z");
}

</style>
