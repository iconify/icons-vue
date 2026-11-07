<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkackqa9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-8-sharp" /></template>
<style>
.fkackqa9b {
  fill: currentColor;
  d: path("M4 20V4h16v16zm5.5-3.5h5v-4L14 12l.5-.5v-4h-5v4l.5.5l-.5.5zm1-5v-3h3v3zm0 4v-3h3v3z");
}

</style>
