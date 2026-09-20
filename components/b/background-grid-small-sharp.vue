<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccjv_yfbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:background-grid-small-sharp" /></template>
<style>
.ccjv_yfbj {
  fill: currentColor;
  d: path("M4 20h3.25v-3.25H4zm4.25 0h3.25v-3.25H8.25zm4.25 0h3.25v-3.25H12.5zm4.25 0H20v-3.25h-3.25zM4 7.25h3.25V4H4zm0 4.25h3.25V8.25H4zm0 4.25h3.25V12.5H4zm4.25-8.5h3.25V4H8.25zm0 4.25h3.25V8.25H8.25zm0 4.25h3.25V12.5H8.25zm4.25-8.5h3.25V4H12.5zm0 4.25h3.25V8.25H12.5zm0 4.25h3.25V12.5H12.5zm4.25-8.5H20V4h-3.25zm0 4.25H20V8.25h-3.25zm0 4.25H20V12.5h-3.25z");
}

</style>
