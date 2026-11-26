<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lyzirz2ep"/><path class="j_efvl6tx"/><path clip-rule="evenodd" class="r5rqf9usu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamond-alert-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j_efvl6tx {
  d: path("M12 7L12 13");
}

.lyzirz2ep {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.7071 6.2929L22.7071 11.2929C22.8946 11.4804 23 11.7348 23 12C23 12.2652 22.8946 12.5196 22.7071 12.7071L12.7071 22.7071C12.5196 22.8946 12.2652 23 12 23C11.7348 23 11.4804 22.8946 11.2929 22.7071L1.2929 12.7071C1.1054 12.5196 1 12.2652 1 12C1 11.7348 1.1054 11.4804 1.2929 11.2929L11.2929 1.2929C11.4804 1.1054 11.7348 1 12 1C12.2652 1 12.5196 1.1054 12.7071 1.2929Z");
  stroke: none;
}

.r5rqf9usu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16C11 15.4477 11.4477 15 12 15C12.5523 15 13 15.4477 13 16Z");
  stroke: none;
}

</style>
