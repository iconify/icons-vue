<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anrk-yt2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hangout-video-sharp" /></template>
<style>
.anrk-yt2b {
  fill: currentColor;
  d: path("M6.923 15.385h6.77v-2.708l3.384 2.708v-6.77l-3.385 2.708V8.616H6.923zM3 19V5h18v14z");
}

</style>
