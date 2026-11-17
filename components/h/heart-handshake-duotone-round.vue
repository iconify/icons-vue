<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="os1jtewbv"/><path class="kco_92qcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-handshake-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kco_92qcs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7c-2-4-9-4-9 2s9 11 9 11s9-5 9-11s-7-6-9-2m0 0l-3 3a2.121 2.121 0 1 0 3 3l1-1a2.83 2.83 0 0 1 4 0l2 2m-4.25 1.25l1.617 1.617M11.5 17.5l1.737 1.737");
}

.os1jtewbv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 7c2-4 9-4 9 2s-9 11-9 11s-9-5-9-11s7-6 9-2");
}

</style>
