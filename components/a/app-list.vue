<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b44qav-eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-list" /></template>
<style>
.b44qav-eg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5v28.363m-8.932-8.779L24 32.863l8.932-8.78m-5.687 16.228c0 1.761-1.453 3.189-3.245 3.189s-3.244-1.428-3.244-3.189s1.452-3.189 3.244-3.189s3.245 1.428 3.245 3.19");
}

</style>
