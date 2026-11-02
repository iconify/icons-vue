<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w0lv7f-we"/><path class="e904trspe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-duotone-sharp" /></template>
<style>
.e904trspe {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6c-1.629 1.629-3 3.515-3 6a9 9 0 0 0 9 9c2.485 0 4.371-1.371 6-3m3-4c.25-.827 0-1.09 0-2a9 9 0 0 0-9-9c-.91 0-1.173-.25-2 0M8 8c-.221 1.117 0 2.698 0 4c0 4.97 1.79 9 4 9m4-5c-.623 3.148-2.369 5-4 5m-9-9h9M2 2l20 20");
}

.ft5dv1b6b {
  fill: none;
}

.w0lv7f-we {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107");
}

</style>
