<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oana6q3yt"/><path class="ih3jxbb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-round-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ih3jxbb2h {
  d: path("M9.5 2L14.5 2L14.5 8.4617C17.2101 9.4979 19 12.0986 19 15C19 18.866 15.866 22 12 22C8.134 22 5 18.866 5 15C5 12.0986 6.7899 9.4979 9.5 8.4617L9.5 2ZM7 2L17 2M5.0718 16L18.9282 16");
}

.oana6q3yt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.5 1L14.5 1C15.0523 1 15.5 1.4477 15.5 2L15.5 7.8063C18.2529 9.1456 20 11.9386 20 15C20 19.4183 16.4183 23 12 23C7.5817 23 4 19.4183 4 15C4 11.9386 5.7471 9.1456 8.5 7.8063L8.5 2C8.5 1.4477 8.9477 1 9.5 1Z");
  stroke: none;
}

</style>
