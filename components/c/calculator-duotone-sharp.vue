<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t6mud7fht"/><path class="mc8vp3qnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mc8vp3qnv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h16v18H4Zm4 9h.01M12 12h.01M8 16h.01M12 16h.01M8 8h8m0 4v4");
}

.t6mud7fht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3h16v18H4Z");
}

</style>
