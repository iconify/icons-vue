<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gs1sv8b-u"/><path class="ycv2ffa9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:import-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gs1sv8b-u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.292 15.707l-2.999-3a.999.999 0 1 1 1.414-1.414L11 12.586V3a1 1 0 0 1 2 0v9.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0Z");
}

.ycv2ffa9v {
  d: path("M4 8v12h16V8h-1a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2Z");
}

</style>
