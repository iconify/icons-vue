<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e961-h68h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-audio-sharp" /></template>
<style>
.e961-h68h {
  fill: currentColor;
  d: path("m6 22l-4-4l4-4l1.425 1.4l-1.6 1.6h12.35L16.6 15.4L18 14l4 4l-4 4l-1.425-1.4l1.6-1.6H5.825L7.4 20.6zm5-9V1h2v12zm-4-2V3h2v8zm8 0V3h2v8zM3 8.5v-3h2v3zm16 0v-3h2v3z");
}

</style>
