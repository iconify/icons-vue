<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lawx5-7et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-pause-corner-fill" /></template>
<style>
.lawx5-7et {
  fill: currentColor;
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293M16 13v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m4 0v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0");
}

</style>
