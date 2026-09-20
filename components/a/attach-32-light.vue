<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i-68b-9_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-32-light" /></template>
<style>
.i-68b-9_j {
  fill: currentColor;
  d: path("m17.077 4.217l-14.93 14.93a.5.5 0 0 0 .707.708l14.93-14.93a6.57 6.57 0 1 1 9.292 9.292L13.287 28.006a3.39 3.39 0 1 1-4.793-4.793l11.86-11.86a.5.5 0 0 0-.708-.707L7.787 22.506a4.39 4.39 0 0 0 6.207 6.207l13.79-13.788A7.57 7.57 0 1 0 17.076 4.217");
}

</style>
