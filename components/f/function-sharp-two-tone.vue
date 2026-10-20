<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzd3yacdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:function-sharp-two-tone" /></template>
<style>
.bzd3yacdx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7219 19.7859L5 20.076C5.5658 20.6663 6.348 21 7.1657 21C8.5051 21 9.6823 20.1121 10.0502 18.8242L13.9498 5.1758C14.3177 3.8879 15.4949 3 16.8343 3C17.652 3 18.4342 3.3337 19 3.924L19.2781 4.2141M7.5 10L17.5 10");
}

</style>
