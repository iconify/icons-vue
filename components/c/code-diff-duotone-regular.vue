<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gnovc0bzy"/><path class="ab_a2hbzz"/><path class="x5i0m055t"/><path class="m1m9ljbml"/><path class="nm1tlbreh"/><path class="e03jjq99j"/><path class="emvotkb4z"/><path class="m26ojxb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-diff-duotone-regular" /></template>
<style>
.ab_a2hbzz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e03jjq99j {
  d: path("M4 7h6");
}

.emvotkb4z {
  d: path("M4 20 20 4");
}

.gnovc0bzy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m1m9ljbml {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m26ojxb3w {
  d: path("M14 17h6");
}

.nm1tlbreh {
  d: path("M7 4v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5i0m055t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
