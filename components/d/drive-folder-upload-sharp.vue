<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skgmo27ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-folder-upload-sharp" /></template>
<style>
.skgmo27ln {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm9-3h2v-4.2l1.6 1.6L16 13l-4-4l-4 4l1.4 1.4l1.6-1.6z");
}

</style>
