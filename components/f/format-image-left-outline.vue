<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xidp2abfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-left-outline" /></template>
<style>
.xidp2abfi {
  fill: currentColor;
  d: path("M4 16.25v-8.5h8.5v8.5zm1-1h6.5v-6.5H5zM4 5V4h16v1zm10.885 3.75v-1H20v1zm0 3.75v-1H20v1zm0 3.75v-1H20v1zM4 20v-1h16v1zm4.25-8");
}

</style>
