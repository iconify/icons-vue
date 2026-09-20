<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkto8vb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-right-outline-sharp" /></template>
<style>
.qkto8vb6o {
  fill: currentColor;
  d: path("M11.5 16.25v-8.5H20v8.5zm1-1H19v-6.5h-6.5zM4 20v-1h16v1zm0-3.75v-1h5.116v1zm0-3.75v-1h5.116v1zm0-3.75v-1h5.116v1zM4 5V4h16v1zm11.75 7");
}

</style>
