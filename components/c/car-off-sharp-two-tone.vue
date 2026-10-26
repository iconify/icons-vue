<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="l9m3cnxup"/><path class="mj4dfabwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l9m3cnxup {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M14.6569 11L7.6569 4L13 4C13.2869 4 13.5601 4.1233 13.7499 4.3385L14.6543 5.3635L18.5717 9.8031L22.3162 11.0513C22.7246 11.1874 23 11.5696 23 12.0001L23 17.0001C23 17.5524 22.5523 18.0001 22 18.0001L21.6569 18L14.6569 11ZM15.1715 18L2 18C1.4477 18 1 17.5523 1 17L1 13C1 12.8925 1.0173 12.7858 1.0513 12.6838L3.718 4.6838C3.7926 4.4596 3.9443 4.2691 4.1461 4.1461L18 18.0001L15.1715 18Z");
  stroke: none;
}

.mj4dfabwy {
  d: path("M4 17L2 17L2 13L4.6667 5L5 5M8 17L15 17M3 10L10 10M8 17C8 18.1046 7.1046 19 6 19C4.8954 19 4 18.1046 4 17C4 15.8954 4.8954 15 6 15C7.1046 15 8 15.8954 8 17ZM18.4142 18.4142C18.0523 18.7761 17.5523 19 17 19C15.8954 19 15 18.1046 15 17C15 16.4477 15.2239 15.9477 15.5858 15.5858M1.7071 1.7071L22.2929 22.2929");
}

</style>
