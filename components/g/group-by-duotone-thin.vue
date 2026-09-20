<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="en35hnbbx"/><path class="e8q-vs_zp"/><path class="i7sqwhbfy"/><path class="qir7x_1xu"/><path class="wf-co-3wj"/><path class="ybh1xwgpp"/><path class="qfe94rk-q"/><path class="ygvoi9umd"/><path class="hxoe7gx5p"/><path class="vox58lg-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-by-duotone-thin" /></template>
<style>
.e8q-vs_zp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.en35hnbbx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.i7sqwhbfy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qfe94rk-q {
  d: path("M2 11h8");
}

.qir7x_1xu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vox58lg-w {
  d: path("M12 11h10");
}

.wf-co-3wj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ybh1xwgpp {
  d: path("M2 5h8");
}

.ygvoi9umd {
  d: path("M2 17h8");
}

</style>
