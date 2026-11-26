<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ur2nqop_b"/><path class="mwfuvgb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d10-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mwfuvgb5l {
  d: path("M12 2.0016L21.9984 12L12 21.9984L2.0016 12ZM8 12L12 2L16 12L12 16ZM2 12L8 12M16 12L22 12M12 16L12 22");
}

.ur2nqop_b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.7063 6.2937L22.7055 11.2929C22.893 11.4804 22.9984 11.7348 22.9984 12C22.9984 12.2652 22.893 12.5196 22.7055 12.7071L12.7071 22.7055C12.5196 22.893 12.2652 22.9984 12 22.9984C11.7348 22.9984 11.4804 22.893 11.2929 22.7055L1.2945 12.7071C1.107 12.5196 1.0016 12.2652 1.0016 12C1.0016 11.7348 1.107 11.4804 1.2945 11.2929L11.2929 1.2945C11.4804 1.107 11.7348 1.0016 12 1.0016C12.2652 1.0016 12.5196 1.107 12.7071 1.2945Z");
  stroke: none;
}

</style>
