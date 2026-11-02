<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ni-uvf29r"/><path class="z1ah1ac9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ni-uvf29r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 6a3 3 0 0 1 3 3v8c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128h-.342a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 4 17V9a3 3 0 0 1 3-3ZM9.705 19.709l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 1 0 0 1.418m4.588-.002l.002.002a1 1 0 1 0 0-1.418l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.z1ah1ac9a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2m-6 0h2m-6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

</style>
