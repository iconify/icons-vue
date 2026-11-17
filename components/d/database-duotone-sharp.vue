<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r7-o7nboi"/><path class="fa-fx9sqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-duotone-sharp" /></template>
<style>
.fa-fx9sqh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3s6-1.343 6-3V7M6 12c0 1.657 2.686 3 6 3s6-1.343 6-3");
}

.ft5dv1b6b {
  fill: none;
}

.r7-o7nboi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 10c-3.314 0-6-1.343-6-3s2.686-3 6-3s6 1.343 6 3s-2.686 3-6 3");
}

</style>
