<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zy5j5tbwm"/><path class="eghs0qcoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eghs0qcoa {
  d: path("M7 2h14a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0V4H7a1 1 0 0 1 0-2M2.293 16.293l5-5a1 1 0 0 1 1.414 0L12 14.586l1.293-1.293a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L14 15.414l-1.293 1.293a1 1 0 0 1-1.414 0L8 13.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414");
}

.zy5j5tbwm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
