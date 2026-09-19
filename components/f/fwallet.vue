<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s3uvwy5gu"/><path class="vv2em8bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fwallet" /></template>
<style>
.s3uvwy5gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 22.882l-11.917 7.266L4.5 22.941m0-.507c0-3.54 2.621-6.411 5.854-6.411h27.292c3.233 0 5.854 2.87 5.854 6.41");
}

.vv2em8bfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.354 9.602h27.292c3.233 0 5.854 2.63 5.854 5.875v17.046c0 3.245-2.621 5.875-5.854 5.875H10.354c-3.233 0-5.854-2.63-5.854-5.875V15.477c0-3.245 2.621-5.875 5.854-5.875");
}

</style>
