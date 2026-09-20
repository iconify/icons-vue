<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="z0-88c71g"/><path class="bk4e95b4i"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="is4rzhsst"/><path class="tc-ybhuxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collapse-block-duotone-thin" /></template>
<style>
.bk4e95b4i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 17 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is4rzhsst {
  d: path("m10 7 2 2 2 -2");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tc-ybhuxl {
  d: path("m10 17 2 -2 2 2");
}

.z0-88c71g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 7 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
