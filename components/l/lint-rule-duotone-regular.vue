<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="icdzo3brn"/><path class="glre06x0r"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="pty_wsbvs"/><path class="zzdenpqnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lint-rule-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.glre06x0r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 15 2.5 -2.5L13 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.icdzo3brn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.pty_wsbvs {
  d: path("M8 9h8");
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zzdenpqnk {
  d: path("m8 15 2.5 -2.5L13 15l2.5 -2.5");
}

</style>
