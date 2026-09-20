<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgc8up6-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:featured-video-sharp" /></template>
<style>
.jgc8up6-p {
  fill: currentColor;
  d: path("M5 14h9V7H5zm-3 6V4h20v16z");
}

</style>
