<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8c4qdyia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-mask-off" /></template>
<style>
.w8c4qdyia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.1292 4.1292C2.8646 4.5128 2 5.6786 2 7L2 17C2 18.6569 3.3431 20 5 20L19 20C19.295 20 19.5885 19.9565 19.8708 19.8708M9.6569 4L19 4C20.6569 4 22 5.3431 22 7L22 16.3431M14.8284 14.8284C14.0783 15.5786 13.0609 16 12 16C9.7909 16 8 14.2091 8 12C8 10.9391 8.4214 9.9217 9.1716 9.1716M2 2L22 22");
}

</style>
