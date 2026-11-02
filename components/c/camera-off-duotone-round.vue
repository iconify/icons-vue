<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hwhi7ybhv"/><path class="bt1xo-0wv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duotone-round" /></template>
<style>
.bt1xo-0wv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 4c.488-.35.535 0 1 0h2c.64 0 1.36.36 2 1l2 2a4 4 0 0 1 4 4v5m-2 4c-.502.227-1.413 0-2 0H7a4 4 0 0 1-4-4v-5c0-1.9 1.224-3.592 3-4m4 4c-.543.543-1 1.172-1 2a3 3 0 0 0 3 3c.828 0 1.457-.457 2-1M2 3l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.hwhi7ybhv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.568 6.018l1.725-1.725C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293l1.725 1.725A5 5 0 0 1 22 11v5a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-5a5 5 0 0 1 4.568-4.982");
}

</style>
