<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="roluv8b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:double-tap-swipe-down-20-regular" /></template>
<style>
.roluv8b-q {
  fill: currentColor;
  d: path("M10.354 17.854a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.708L9.5 16.293V7.5a.5.5 0 0 1 1 0v8.793l2.146-2.147a.5.5 0 0 1 .708.708zM4.5 7.5a5.5 5.5 0 0 0 4 5.293v-1.05A4.502 4.502 0 0 1 10 3a4.5 4.5 0 0 1 1.5 8.744v1.049a5.5 5.5 0 1 0-7-5.293m2 0a3.5 3.5 0 0 0 2 3.163V9.5a2.5 2.5 0 1 1 3 0v1.163a3.5 3.5 0 1 0-5-3.163");
}

</style>
