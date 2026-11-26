<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sg7iid8ts"/><path class="ow9i-bbyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-terminator-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow9i-bbyu {
  d: path("M9 5L15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L9 19C5.134 19 2 15.866 2 12C2 8.134 5.134 5 9 5Z");
}

.sg7iid8ts {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6569 6.3431C22.1035 7.7898 23 9.7911 23 12C23 16.4183 19.4183 20 15 20L9 20C4.5817 20 1 16.4183 1 12C1 7.5817 4.5817 4 9 4L15 4C17.2089 4 19.2102 4.8965 20.6569 6.3431Z");
  stroke: none;
}

</style>
