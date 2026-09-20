<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz1z5bc0f"/><path class="nvmq33b0q"/><path class="ctm-gvblg"/><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lightning-bolt-duotone-regular" /></template>
<style>
.ctm-gvblg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 14 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.flblq5ico {
  d: path("m13 14 6 6");
}

.lz1z5bc0f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 2 -8 8h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mbgtdkbsk {
  d: path("m16 2 -8 8h5l-8 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvmq33b0q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zsil77j-s {
  d: path("m19 14 -6 6");
}

</style>
