<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z7iu_qbsd"/><path class="g8ge0y5fo"/><path class="f7kl6pbji"/><path class="vgx27qokn"/><path class="o8scmcc3i"/><path class="vsmfi0bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:login-duotone-regular" /></template>
<style>
.f7kl6pbji {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g8ge0y5fo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8scmcc3i {
  d: path("M3 12h10");
}

.vgx27qokn {
  d: path("M15 3h6v18h-6");
}

.vsmfi0bcq {
  d: path("m10 9 3 3 -3 3");
}

.z7iu_qbsd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 3h6v18h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
