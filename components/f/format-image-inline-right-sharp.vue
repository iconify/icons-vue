<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4l7_bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-inline-right-sharp" /></template>
<style>
.yl4l7_bjt {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm7.5-3.75v-8.5H20v8.5zM4 5V4h16v1zm0 11.25v-1h4.73v1z");
}

</style>
