<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mpvxijbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blue-archive-alt" /></template>
<style>
.mpvxijbqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.736 4.516L9.79 43.484M8.249 10.253L39.75 29.108m-3.132-2.498c-2.248 3.94-9.858 3.83-16.998-.246q0 0 0 0c-7.14-4.075-11.105-10.572-8.857-14.51v-.001c2.249-3.939 9.859-3.828 16.998.247s11.104 10.571 8.857 14.51");
}

</style>
