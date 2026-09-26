<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vv0uoyjwr"/><path class="x9obmne9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vv0uoyjwr {
  stroke-opacity: 0.4;
  d: path("M6 2L6 10M2.7071 6.7071L6 10L9.2929 6.7071M6 22L6 14M2.7071 17.2929L6 14L9.2929 17.2929");
}

.x9obmne9u {
  d: path("M12 6L22 6M12 12L22 12M12 18L22 18");
}

</style>
