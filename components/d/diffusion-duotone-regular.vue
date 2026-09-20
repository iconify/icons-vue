<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mgc5w0bas"/><path class="nfsra8bqu"/><path class="nw8-8vb0d"/><path class="tt9689b6q"/><path class="gt7coxqxq"/><path class="gvmht2kii"/><path class="iedujiqkb"/><path class="rvtpkuisl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diffusion-duotone-regular" /></template>
<style>
.gt7coxqxq {
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gvmht2kii {
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mgc5w0bas {
  fill: currentColor;
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nfsra8bqu {
  fill: currentColor;
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.nw8-8vb0d {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rvtpkuisl {
  d: path("M12 8a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

.tt9689b6q {
  fill: currentColor;
  d: path("M12 8a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
