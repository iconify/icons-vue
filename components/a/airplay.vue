<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2is6ybzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airplay" /></template>
<style>
.r2is6ybzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.1043 15.8632C2.8523 15.4715 2 14.3118 2 13L2 6C2 4.3431 3.3431 3 5 3L19 3C20.6569 3 22 4.3431 22 6L22 13C22 14.3118 21.1477 15.4715 19.8957 15.8632M12.8 14.0667L16.8 19.4C17.2944 20.0592 16.824 21 16 21L8 21C7.176 21 6.7056 20.0592 7.2 19.4L11.2 14.0667C11.6 13.5333 12.4 13.5333 12.8 14.0667Z");
}

</style>
