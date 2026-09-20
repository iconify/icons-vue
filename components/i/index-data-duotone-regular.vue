<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ly2hozbzp"/><path class="tvpgdo31a"/><path class="lpaeqt_qp"/><path class="bbj1r8bpd"/><path class="ucd51obdt"/><path class="wj36vd5ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-data-duotone-regular" /></template>
<style>
.bbj1r8bpd {
  d: path("M4 14h12");
}

.lpaeqt_qp {
  d: path("M4 9h12");
}

.ly2hozbzp {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tvpgdo31a {
  d: path("M2 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ucd51obdt {
  d: path("M19 6v12");
}

.wj36vd5ho {
  d: path("m17 16 2 2 2 -2");
}

</style>
