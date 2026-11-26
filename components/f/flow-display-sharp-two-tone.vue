<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bi77rtbtm"/><path class="ndp81xbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-display-sharp-two-tone" /></template>
<style>
.bi77rtbtm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6569 6.3431C22.1035 7.7898 23 9.7911 23 12C23 16.4183 19.4183 20 15 20L8 20C7.708 20 7.4306 19.8724 7.2406 19.6506L1.2429 12.6506C1.0876 12.4694 1.0023 12.2386 1.0023 12C1.0023 11.7614 1.0876 11.5306 1.2429 11.3494L7.2406 4.3494C7.4306 4.1276 7.708 4 8 4L15 4C17.2089 4 19.2102 4.8965 20.6569 6.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ndp81xbxq {
  d: path("M15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L8 19L2.0023 12L8 5Z");
}

</style>
