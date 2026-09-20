<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjdig4dxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-color-outline-sharp" /></template>
<style>
.rjdig4dxm {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm4-8h1.4l7.8-7.775l-.725-.725l-.7-.7L6 14.6zm-2 2v-4.25l12.625-12.6l4.2 4.275L8.25 18zM18 5.4L16.6 4zm-2.8 2.825l-.725-.725l-.7-.7z");
}

</style>
