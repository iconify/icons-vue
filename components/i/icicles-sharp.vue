<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="auakfdcez"/><path class="pzhmyob9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:icicles-sharp" /></template>
<style>
.auakfdcez {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.35 3.75h17.9V7l-.21.56l-1.83 4.88L19 13l-.21-.56l-1.83-4.88l-.21-.56h-2.5l-.18.57l-1.89 5.86L12 14l-.18-.57l-1.89-5.86L9.75 7h-2.5l-.21.56l-1.83 4.88L5 13l-.21-.56l-1.83-4.88L2.75 7V3.75z");
}

.pzhmyob9w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
