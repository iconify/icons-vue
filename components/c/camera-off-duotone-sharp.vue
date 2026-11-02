<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hrlxo52nt"/><path class="gd6_33bwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gd6_33bwd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 20H3V7h3m4-3zh4l3 3h4v9m-11-5c-.543.543-1 1.172-1 2a3 3 0 0 0 3 3c.828 0 1.457-.457 2-1M2 3l19 19");
}

.hrlxo52nt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.586 6l2.707-2.707A1 1 0 0 1 10 3h4c.265 0 .52.105.707.293L17.414 6H21a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Z");
}

</style>
