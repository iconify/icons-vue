<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o73djqzge"/><path class="bzpq9_bwx"/><path class="e0ypuygzg"/><path class="uy8z00bnt"/><path class="a7n0rwu5e"/><path class="rf4kl9b8f"/><path class="ritvf8n1n"/><path class="hynwb207w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessible-duotone-regular" /></template>
<style>
.a7n0rwu5e {
  d: path("M2 18v-5h5V8h5");
}

.bzpq9_bwx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e0ypuygzg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hynwb207w {
  d: path("M19 15v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o73djqzge {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18v-5h5V8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rf4kl9b8f {
  d: path("m12 8 7 7");
}

.ritvf8n1n {
  d: path("M2 18h17");
}

.uy8z00bnt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
