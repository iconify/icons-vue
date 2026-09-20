<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ds26vtn9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:car-simple-thin" /></template>
<style>
.ds26vtn9z {
  fill: currentColor;
  d: path("M240 108h-13.4l-28.83-64.87a12 12 0 0 0-11-7.13H69.2a12 12 0 0 0-11 7.13L29.4 108H16a4 4 0 0 0 0 8h12v84a12 12 0 0 0 12 12h24a12 12 0 0 0 12-12v-20h104v20a12 12 0 0 0 12 12h24a12 12 0 0 0 12-12v-84h12a4 4 0 0 0 0-8M65.54 46.38A4 4 0 0 1 69.2 44h117.6a4 4 0 0 1 3.66 2.38L217.84 108H38.16ZM220 200a4 4 0 0 1-4 4h-24a4 4 0 0 1-4-4v-24a4 4 0 0 0-4-4H72a4 4 0 0 0-4 4v24a4 4 0 0 1-4 4H40a4 4 0 0 1-4-4v-84h184Z");
}

</style>
