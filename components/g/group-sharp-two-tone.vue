<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f93tp4-mo"/><path class="cgbq5dbea"/><path clip-rule="evenodd" class="dpgk2uboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:group-sharp-two-tone" /></template>
<style>
.cgbq5dbea {
  d: path("M16 19L16 22L2 22L2 8L5 8M8 16L22 16L22 2L8 2L8 16Z");
}

.dpgk2uboc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 6.5C14 7.3285 13.3285 8 12.5 8C11.6715 8 11 7.3285 11 6.5C11 5.6715 11.6715 5 12.5 5C13.3285 5 14 5.6715 14 6.5ZM19 6.5C19 7.3285 18.3285 8 17.5 8C16.6715 8 16 7.3285 16 6.5C16 5.6715 16.6715 5 17.5 5C18.3285 5 19 5.6715 19 6.5ZM19 11.5C19 12.3285 18.3285 13 17.5 13C16.6715 13 16 12.3285 16 11.5C16 10.6715 16.6715 10 17.5 10C18.3285 10 19 10.6715 19 11.5Z");
  stroke: none;
}

.f93tp4-mo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 17L22 17C22.5523 17 23 16.5523 23 16L23 2C23 1.4477 22.5523 1 22 1L8 1C7.4477 1 7 1.4477 7 2L7 16C7 16.5523 7.4477 17 8 17Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
