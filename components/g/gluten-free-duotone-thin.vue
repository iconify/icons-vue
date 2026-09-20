<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj8ybccjk"/><path class="s15bau5qf"/><path class="psu4-5k5s"/><path class="ct6gzwbxg"/><path class="gia5-zjad"/><path class="ireg5-o3k"/><path class="r7xk8o29f"/><path class="v4iyegbro"/><path class="xhssufbfj"/><path class="bydm5bjkj"/><path class="c3g7d7t3t"/><path class="emvotkb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gluten-free-duotone-thin" /></template>
<style>
.bydm5bjkj {
  d: path("m12 14 -4 -4");
}

.c3g7d7t3t {
  d: path("m12 14 4 -4");
}

.ct6gzwbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 14 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.emvotkb4z {
  d: path("M4 20 20 4");
}

.gia5-zjad {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 14 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ireg5-o3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.psu4-5k5s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s15bau5qf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9 8 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v4iyegbro {
  d: path("M12 9 8 5");
}

.wj8ybccjk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhssufbfj {
  d: path("m12 9 4 -4");
}

</style>
