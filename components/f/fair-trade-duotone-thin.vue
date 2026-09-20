<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj8ybccjk"/><path class="b7h8iyqlm"/><path class="ne413abhf"/><path class="fenqk1bqx"/><path class="drz60ab5x"/><path class="r7xk8o29f"/><path class="k4qo1xe9v"/><path class="bai-ikdbm"/><path class="qorafhbcl"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fair-trade-duotone-thin" /></template>
<style>
.b7h8iyqlm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bai-ikdbm {
  d: path("M9 6a3 3 0 0 1 -6 0");
}

.drz60ab5x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fenqk1bqx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.ne413abhf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qorafhbcl {
  d: path("M21 6a3 3 0 0 1 -6 0");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.wj8ybccjk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
