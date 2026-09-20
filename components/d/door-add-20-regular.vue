<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pha5toblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-add-20-regular" /></template>
<style>
.pha5toblc {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M14 2a2 2 0 0 1 2 2v5.208a5.5 5.5 0 0 0-1-.185V4a1 1 0 0 0-1-1H6a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h3.602q.274.538.656 1H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm.5 10a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M7 9a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
