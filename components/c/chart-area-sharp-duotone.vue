<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="qahw4wbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p53xcyb3q {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

.qahw4wbvb {
  fill: currentColor;
  d: path("M6.2929 14.2929L12.2929 8.2929C12.4804 8.1054 12.7348 8 13 8C13.2652 8 13.5196 8.1054 13.7071 8.2929L16 10.5858L20.2929 6.2929C20.4804 6.1054 20.7348 6 21 6C21.5523 6 22 6.4477 22 7L22 17C22 17.5523 21.5523 18 21 18L7 18C6.4477 18 6 17.5523 6 17L6 15C6 14.7348 6.1054 14.4804 6.2929 14.2929Z");
  stroke: none;
}

</style>
