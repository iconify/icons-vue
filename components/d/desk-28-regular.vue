<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dh4xfvb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-28-regular" /></template>
<style>
.dh4xfvb0z {
  fill: currentColor;
  d: path("M23.251 4a2.75 2.75 0 0 1 2.75 2.75v16.5a.75.75 0 0 1-1.5 0V10.5H14l.001 10.75a2.75 2.75 0 0 1-2.75 2.75H4.754a2.75 2.75 0 0 1-2.75-2.75V6.75A2.75 2.75 0 0 1 4.754 4zM3.504 21.25c0 .69.56 1.25 1.25 1.25h6.497c.69 0 1.25-.56 1.25-1.25L12.5 10.5H3.504zM9.75 13a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zM4.754 5.5c-.69 0-1.25.56-1.25 1.25V9H24.5V6.75c0-.69-.56-1.25-1.25-1.25z");
}

</style>
