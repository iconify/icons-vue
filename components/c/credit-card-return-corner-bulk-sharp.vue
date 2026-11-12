<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ywi0h9bjw"/><path class="iu4_dq41x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-return-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iu4_dq41x {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m19 9a1 1 0 0 1-1 1h-5.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L15.414 16H20v-3a1 1 0 0 1 2 0Z");
}

.ywi0h9bjw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9H10v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Z");
}

</style>
