<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zez4zgfxm"/><path class="e8vhesj2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-duotone-round" /></template>
<style>
.e8vhesj2h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12v4.313a2 2 0 0 1-1.114 1.793l-7 3.457a2 2 0 0 1-1.772 0l-7-3.457A2 2 0 0 1 3 16.313V7.687a2 2 0 0 1 1.114-1.793l7-3.457a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687zM3.32 6.602L12 10.89l8.68-4.287M12 10.89v10.88");
}

.ft5dv1b6b {
  fill: none;
}

.zez4zgfxm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 16.313a3 3 0 0 1-1.672 2.69l-7 3.456a3 3 0 0 1-2.656 0l-7-3.456A3 3 0 0 1 2 16.313V7.687c0-1.141.648-2.184 1.672-2.69l7-3.456a3 3 0 0 1 2.656 0l7 3.456A3 3 0 0 1 22 7.687Z");
}

</style>
