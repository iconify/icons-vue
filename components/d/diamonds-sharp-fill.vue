<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zl_tp4r4f"/><path clip-rule="evenodd" class="xg83mzbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamonds-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xg83mzbku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.2071 7.7929L22.7071 11.2929C22.8946 11.4804 23 11.7348 23 12C23 12.2652 22.8946 12.5196 22.7071 12.7071L15.7071 19.7071C15.5196 19.8946 15.2652 20 15 20C14.7348 20 14.4804 19.8946 14.2929 19.7071L7.2929 12.7071C7.1054 12.5196 7 12.2652 7 12C7 11.7348 7.1054 11.4804 7.2929 11.2929L14.2929 4.2929C14.4804 4.1054 14.7348 4 15 4C15.2652 4 15.5196 4.1054 15.7071 4.2929Z");
  stroke: none;
}

.zl_tp4r4f {
  d: path("M9.8787 5.8787L9 5L2 12L9 19L9.8787 18.1213");
}

</style>
