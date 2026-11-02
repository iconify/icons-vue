<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ngy69lg9f"/><path class="fomw097yp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duotone" /></template>
<style>
.fomw097yp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 4c.488-.35.535 0 1 0h2c.64 0 1.36.36 2 1l2 2h2a2 2 0 0 1 2 2v7m-2 4H5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1m4 4c-.543.543-1 1.172-1 2a3 3 0 0 0 3 3c.828 0 1.457-.457 2-1M2 3l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.ngy69lg9f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.586 6l1.707-1.707C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6H19a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Z");
}

</style>
