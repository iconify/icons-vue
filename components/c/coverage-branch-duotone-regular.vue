<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="s2vluwbri"/><path class="twp0pibjo"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e8t0a9beq"/><path class="zn6_kf4ff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coverage-branch-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e8t0a9beq {
  d: path("M12 7v4l-4 4");
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s2vluwbri {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v4l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.twp0pibjo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 11 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zn6_kf4ff {
  d: path("m12 11 4 4");
}

</style>
