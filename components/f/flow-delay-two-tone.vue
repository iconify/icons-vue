<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p4j3vnywu"/><path class="lgjmden8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-delay-two-tone" /></template>
<style>
.lgjmden8o {
  d: path("M5 5L15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L5 19C3.3431 19 2 17.6569 2 16L2 8C2 6.3431 3.3431 5 5 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4j3vnywu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6569 6.3431C22.1035 7.7898 23 9.7911 23 12C23 16.4183 19.4183 20 15 20L5 20C2.7908 20 1 18.2092 1 16L1 8C1 5.7908 2.7908 4 5 4L15 4C17.2089 4 19.2102 4.8965 20.6569 6.3431Z");
  stroke: none;
}

</style>
