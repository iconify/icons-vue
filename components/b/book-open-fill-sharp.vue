<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4_y1sbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-fill-sharp" /></template>
<style>
.j4_y1sbnt {
  fill: currentColor;
  d: path("M8.586 18H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-5.586l-2.707 2.707a1 1 0 0 1-1.414 0ZM13 6a1 1 0 0 0-2 0v9a1 1 0 0 0 2 0Z");
}

</style>
