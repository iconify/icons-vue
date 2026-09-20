<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3caa40ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-outline-sharp" /></template>
<style>
.j3caa40ls {
  fill: currentColor;
  d: path("m13.6 14l-1.3-1.3l-1.3-1.3l-5 5L8.6 19zm-1.175-4.025l1.3 1.3l1.3 1.3L20 7.6L17.4 5zM1.5 21l3.15-3.15l-.75-.75v-1.4l6.425-6.425l5.4 5.4L9.3 21.1H7.9l-.75-.75l-.65.65zm8.825-11.725L17.4 2.2l5.4 5.4l-7.075 7.075z");
}

</style>
