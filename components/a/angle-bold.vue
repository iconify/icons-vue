<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yzt87znoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:angle-bold" /></template>
<style>
.yzt87znoj {
  fill: currentColor;
  d: path("M252 200a12 12 0 0 1-12 12H72a12 12 0 0 1-12-12V84H32a12 12 0 0 1 0-24h28V32a12 12 0 0 1 24 0v156h156a12 12 0 0 1 12 12M111 84.29a84 84 0 0 1 76.7 76.7a12 12 0 0 0 11.95 11h1a12 12 0 0 0 11-13A108 108 0 0 0 113 60.37a12 12 0 1 0-2 23.92");
}

</style>
