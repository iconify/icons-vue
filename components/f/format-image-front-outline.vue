<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zky1t7bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-front-outline" /></template>
<style>
.zky1t7bxb {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h1.866v1zm3.75 0v-8.5h8.5v8.5zm10.385 0v-1H20v1zm-9.385-1h6.5v-6.5h-6.5zM4 12.5v-1h1.866v1zm14.135 0v-1H20v1zM4 8.75v-1h1.866v1zm14.135 0v-1H20v1zM4 5V4h16v1zm8 7");
}

</style>
