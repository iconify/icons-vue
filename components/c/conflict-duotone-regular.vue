<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6u-_7r8k"/><path class="e948e9bse"/><path class="s__5d7blq"/><path class="wtehq4bsj"/><path class="bs41d9oln"/><path class="erdfj7vbx"/><path class="o_nzgwnjk"/><path class="vtgsa7bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:conflict-duotone-regular" /></template>
<style>
.bs41d9oln {
  d: path("m3 3 5 5");
}

.e948e9bse {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 7v3.5H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.erdfj7vbx {
  d: path("M10.5 7v3.5H7");
}

.j6u-_7r8k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 3 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_nzgwnjk {
  d: path("m21 21 -5 -5");
}

.s__5d7blq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 21 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vtgsa7bep {
  d: path("M13.5 17v-3.5H17");
}

.wtehq4bsj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 17v-3.5H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
