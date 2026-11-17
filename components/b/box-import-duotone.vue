<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jl4rwabie"/><path class="trp7odh6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jl4rwabie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 10.889V21a.623.623 0 0 1-.897.557l-7.546-3.726A1 1 0 0 1 3 16.934V7.066a1 1 0 0 1 .557-.897l8-3.95a1 1 0 0 1 .886 0l7.66 3.783a.493.493 0 0 1 0 .885Z");
}

.trp7odh6o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V7.066a1 1 0 0 0-.557-.897L16.5 4.222m0 0L12.443 2.22a1 1 0 0 0-.886 0l-8 3.95A1 1 0 0 0 3 7.066v9.868a1 1 0 0 0 .557.897l7.546 3.726A.62.62 0 0 0 12 21V10.889M3.16 6.523L12 10.89l8.84-4.366M18 15l-3 3l3 3m-3-3h6");
}

</style>
