<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyqn26vzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-share-outline-sharp" /></template>
<style>
.wyqn26vzz {
  fill: currentColor;
  d: path("M10 17v-5h6.175L14.6 10.4L16 9l4 4l-4 4l-1.425-1.425l1.6-1.575H12v3zm-3 5V4h3V2h4v2h3v4h-2V6H9v14h6v-2h2v4z");
}

</style>
