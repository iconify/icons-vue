<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbx8vy1yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-sharp" /></template>
<style>
.fbx8vy1yx {
  fill: currentColor;
  d: path("m1.5 21l3.15-3.15l-.75-.75v-1.4L9.6 10l5.4 5.4l-5.7 5.7H7.9l-.75-.75l-.65.65zm9.525-12.425L17.4 2.2l5.4 5.4l-6.375 6.375z");
}

</style>
