<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r2zd56b1a"/><path class="ppbm5y1-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:earbuds-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ppbm5y1-m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4c2 0 4 1 4 3v13c0 1-2 1-2 0V10H6q-3 0-3-3t3-3m12 0c-2 0-4 1-4 3v13c0 1 2 1 2 0V10h2q3 0 3-3t-3-3M6 7h.01M18 7h.01");
}

.r2zd56b1a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 7v13c0 .571-.286 1.08-.758 1.395c-.924.615-2.433.443-3.02-.563A1.65 1.65 0 0 1 7 20v-9H6c-1.079 0-2.172-.259-2.957-1.043C2.259 9.172 2 8.079 2 7s.259-2.172 1.043-2.957C3.828 3.259 4.921 3 6 3c1.706 0 3.617.636 4.52 2.184c.322.551.48 1.179.48 1.816m7 4h-1v9c0 .292-.075.579-.222.832c-.587 1.006-2.096 1.178-3.02.563A1.67 1.67 0 0 1 13 20V7c0-.637.158-1.265.48-1.816C14.383 3.636 16.294 3 18 3c1.079 0 2.172.259 2.957 1.043C21.741 4.828 22 5.921 22 7s-.259 2.172-1.043 2.957C20.172 10.741 19.079 11 18 11");
}

</style>
