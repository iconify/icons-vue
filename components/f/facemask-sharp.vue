<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzi28vayc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:facemask-sharp" /></template>
<style>
.qzi28vayc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.091 14.5H2V8.5H8L12 6L16.222 8.5H22V14.5H16.909M6 8.5L6.513 12.44C6.734 14.13 7.508 15.66 8.669 16.68C10.643 18.43 13.357 18.43 15.331 16.68C16.493 15.66 17.266 14.13 17.487 12.44L18 8.5M12 10V15");
}

</style>
