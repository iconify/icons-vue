<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u21a955zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-right-sharp" /></template>
<style>
.u21a955zz {
  fill: currentColor;
  d: path("M11.5 16.25v-8.5H20v8.5zM4 20v-1h16v1zm0-3.75v-1h5.116v1zm0-3.75v-1h5.116v1zm0-3.75v-1h5.116v1zM4 5V4h16v1z");
}

</style>
