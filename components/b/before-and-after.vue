<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxizowblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after" /></template>
<style>
.fxizowblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V5M12 5V19M12 5H19C20.6569 5 22 6.3431 22 8V16C22 17.6569 20.6569 19 19 19H12M12 19V22M8 19H5C3.3431 19 2 17.6569 2 16V8C2 6.3431 3.3431 5 5 5H8");
}

</style>
