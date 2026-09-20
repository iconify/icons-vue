<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="xr89y0boe"/><path class="bdw22rb9m"/><path class="skbifdbcx"/><path class="zj4mz4frt"/><path class="shm5lmr1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-merge-duotone-regular" /></template>
<style>
.bdw22rb9m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 15 -4 -4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kosxb-loy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shm5lmr1k {
  d: path("m21 15 -4 -4h-4");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.xr89y0boe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 11v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zj4mz4frt {
  d: path("M21 11v10");
}

</style>
