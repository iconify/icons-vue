<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vam4psdav"/><path class="hwukxflcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hwukxflcq {
  stroke-opacity: 0.4;
  d: path("M12 3L15.3333 3M17.3333 3L21 3L21 6.6667M21 8.6667L21 12");
}

.vam4psdav {
  d: path("M10 18L21 18M17.7071 21.2929L21 18L17.7071 14.7071M6 14L6 3M9.2929 6.2929L6 3L2.7071 6.2929");
}

</style>
