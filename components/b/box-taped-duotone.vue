<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nopz2lbuv"/><path class="k8rrfq4pg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k8rrfq4pg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12v4.934a1 1 0 0 1-.557.897l-8 3.95a1 1 0 0 1-.886 0l-8-3.95A1 1 0 0 1 3 16.934V7.066a1 1 0 0 1 .557-.897l8-3.95a1 1 0 0 1 .886 0l8 3.95a1 1 0 0 1 .557.897zM3.16 6.523L12 10.89l8.84-4.366M12 10.89v10.996M7.5 4.222l9 4.445");
}

.nopz2lbuv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 7.066v9.868a2 2 0 0 1-1.114 1.793l-8 3.951a2 2 0 0 1-1.772 0l-8-3.951A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l8-3.951a2 2 0 0 1 1.772 0l8 3.951A2 2 0 0 1 22 7.066");
}

</style>
