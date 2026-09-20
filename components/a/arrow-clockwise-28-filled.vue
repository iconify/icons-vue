<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="l0g4wtb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-clockwise-28-filled" /></template>
<style>
.l0g4wtb8f {
  fill: currentColor;
  d: path("M19.658 7A8.96 8.96 0 0 0 14 5a9 9 0 1 0 8.956 8.099a1 1 0 0 1 1.99-.198Q25 13.444 25 14c0 6.075-4.925 11-11 11S3 20.075 3 14S7.925 3 14 3c2.66 0 5.099.944 7 2.514V4a1 1 0 1 1 2 0v4.029A1 1 0 0 1 22 9h-4a1 1 0 1 1 0-2z");
}

</style>
