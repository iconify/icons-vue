<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aezsu9biz"/><path class="p9ingombl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-duotone-sharp" /></template>
<style>
.aezsu9biz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0h-.342a3 3 0 0 1-5.658 0H5a1 1 0 0 1-1-1Zm5.705 12.709l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 1 0 0 1.418m4.588-.002l.002.002a1 1 0 1 0 0-1.418l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.ft5dv1b6b {
  fill: none;
}

.p9ingombl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19H5V7h14v12h-2m-6 0h2m-6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V3h6v4");
}

</style>
