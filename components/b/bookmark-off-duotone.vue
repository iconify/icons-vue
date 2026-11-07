<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k-t_b5bqe"/><path class="gqbjtbcmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gqbjtbcmw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h4a2 2 0 0 1 2 2v5m0 6v1c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6c0-.293.063-.572.177-.823M3 2l19 19");
}

.k-t_b5bqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h5a2.003 2.003 0 0 1 2 2v5Zm7 14c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6c0-.284.059-.565.177-.823L18 17Z");
}

</style>
