<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a7n0rwu5e"/><path class="rf4kl9b8f"/><path class="ritvf8n1n"/><path class="hynwb207w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessible-outline-regular" /></template>
<style>
.a7n0rwu5e {
  d: path("M2 18v-5h5V8h5");
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

.rf4kl9b8f {
  d: path("m12 8 7 7");
}

.ritvf8n1n {
  d: path("M2 18h17");
}

</style>
