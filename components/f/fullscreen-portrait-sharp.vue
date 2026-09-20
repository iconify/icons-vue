<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd8-vz0rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fullscreen-portrait-sharp" /></template>
<style>
.dd8-vz0rt {
  fill: currentColor;
  d: path("M8.385 17.616h7.23V6.385h-7.23zM19 21H5V3h14z");
}

</style>
