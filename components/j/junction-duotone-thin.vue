<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmnj_rj7a"/><path class="uakhv-9cy"/><path class="wh_0_1bjo"/><path class="bf72izbtx"/><path class="zwn3rtbhc"/><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:junction-duotone-thin" /></template>
<style>
.bf72izbtx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 22v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfwe2fbcx {
  d: path("M8 22v-6H2");
}

.gaonsmbbz {
  d: path("M16 22v-6h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7mb9vbwf {
  d: path("M8 2v6H2");
}

.uakhv-9cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 2v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v3qgglbcl {
  d: path("M12 9.5v5");
}

.wh_0_1bjo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 22v-6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_6spmb5u {
  d: path("M16 2v6h6");
}

.zmnj_rj7a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 2v6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwn3rtbhc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
