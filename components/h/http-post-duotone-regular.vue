<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="xjfy82bzs"/><path class="m_9p98blm"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e84lw4bzo"/><path class="ri_favbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-post-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e84lw4bzo {
  d: path("M12 10v5.5");
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.m_9p98blm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 12.5 12 10l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ri_favbdz {
  d: path("M9.5 12.5 12 10l2.5 2.5");
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xjfy82bzs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
