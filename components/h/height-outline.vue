<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqqr7selq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:height-outline" /></template>
<style>
.iqqr7selq {
  fill: currentColor;
  d: path("m12 21l-4-4l1.4-1.4l1.6 1.575V6.825L9.4 8.4L8 7l4-4l4 4l-1.4 1.425l-1.6-1.6v10.35l1.6-1.575L16 17z");
}

</style>
