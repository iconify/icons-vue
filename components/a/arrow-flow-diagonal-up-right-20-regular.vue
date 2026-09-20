<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewut9fbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-diagonal-up-right-20-regular" /></template>
<style>
.ewut9fbtu {
  fill: currentColor;
  d: path("M10.5 4a.5.5 0 0 0 0 1h3.793l-6.555 6.555a3 3 0 1 0 .707.707L15 5.708V9.5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5zM4 14a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

</style>
