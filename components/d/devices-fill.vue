<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r593u2bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-fill" /></template>
<style>
.r593u2bob {
  fill: currentColor;
  d: path("M15 5H5a.997.997 0 0 0-1 1v8a.997.997 0 0 0 1 1h6a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3a1 1 0 0 1-2 0a1 1 0 0 0-1-1m-1 7a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

</style>
