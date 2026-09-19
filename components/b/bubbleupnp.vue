<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xvmq39-2k"/><path class="b7l2n-b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubbleupnp" /></template>
<style>
.b7l2n-b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.216 36.83a18.304 18.304 0 0 0-1.19-25.142m-3.91 20.455a11.36 11.36 0 0 0-.73-15.42M15.25 24.36a5.751 5.751 0 1 1 0 11.497H5.5V12.86h9.75a5.85 5.85 0 0 1 5.91 5.749a5.85 5.85 0 0 1-5.91 5.749Zm0-.001H5.5");
}

.xvmq39-2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.25 41.457a25.17 25.17 0 0 0-1.654-34.914");
}

</style>
