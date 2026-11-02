<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d1ajjbb6o"/><path class="aj0c2vbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone-round" /></template>
<style>
.aj0c2vbdr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 10l1 3l-7 7a1.414 1.414 0 0 1-2 0l-7-7l1-3V5c0-.738.631-1.369 1-1l3 3c.64.64 1.72 1 3 1s2.36-.36 3-1l3-3c.369-.369 1 .262 1 1zM9 12l1 1m5-1l-1 1m-2 3h.01");
}

.d1ajjbb6o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20 9.838l.949 2.846c.119.359.026.755-.242 1.023l-7 7a2.414 2.414 0 0 1-3.414 0l-7-7a1 1 0 0 1-.242-1.023L4 9.838V5c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l3 3c.948.948 3.638.948 4.586 0l3-3c.31-.311.752-.456 1.186-.382C19.428 3.072 20 4.102 20 5Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
