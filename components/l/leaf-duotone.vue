<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l7j7kfblz"/><path class="dg-key1ae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-duotone" /></template>
<style>
.dg-key1ae {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17c7 4 13-1 12-12C8 4 3 10 7 17m-3 3l3-3m0 0l6-6");
}

.ft5dv1b6b {
  fill: none;
}

.l7j7kfblz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.132 17.496c-3.352-5.867-.911-11.24 5.527-12.992c2.413-.656 4.953-.725 7.432-.5c.48.044.861.425.905.905c.225 2.479.156 5.019-.5 7.432a12.5 12.5 0 0 1-1.135 2.833c-1.912 3.411-5.258 4.9-9.055 3.875a12 12 0 0 1-2.802-1.181a1 1 0 0 1-.372-.372");
}

</style>
