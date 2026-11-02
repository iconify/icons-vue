<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ho_bnqblo"/><path class="ls7iozbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-donut-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ho_bnqblo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ls7iozbbd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m5 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m4-9v5m4 4h5");
}

</style>
