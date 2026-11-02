<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-kp1hia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-text-fill-sharp" /></template>
<style>
.c_-kp1hia {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-4 3a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm6 4H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
