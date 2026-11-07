<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rh_f2zbxx"/><path class="fzv_4uflo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fzv_4uflo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19H7A5 5 0 0 1 7 9q.112-.39.252-.748m2.726-3.274C13.338 3.11 18 5.242 18 11a4 4 0 0 1 3.646 5.647M2 3l19 19");
}

.rh_f2zbxx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.978 4.978C13.337 3.11 18 5.242 18 11a4 4 0 0 1 3.646 5.646ZM7 19A5 5 0 0 1 7 9q.108-.38.252-.748L18 19Z");
}

</style>
