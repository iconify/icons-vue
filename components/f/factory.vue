<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0tpmuwdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:factory" /></template>
<style>
.n0tpmuwdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 19L2 4C2 3.4477 2.4477 3 3 3L6 3C6.5523 3 7 3.4477 7 4L7 10.1169C7 10.5056 7.424 10.7456 7.7572 10.5457L11.2428 8.4543C11.576 8.2544 12 8.4944 12 8.8831L12 10.1169C12 10.5056 12.424 10.7456 12.7572 10.5457L16.2428 8.4543C16.576 8.2544 17 8.4944 17 8.8831L17 10.1169C17 10.5056 17.424 10.7456 17.7572 10.5457L21.2428 8.4543C21.576 8.2544 22 8.4944 22 8.8831L22 19C22 20.1046 21.1046 21 20 21L4 21C2.8954 21 2 20.1046 2 19ZM2 7L7 7M11 4.5C11 3.6716 11.6716 3 12.5 3L22 3M10 15L10 17M14 15L14 17M18 15L18 17");
}

</style>
