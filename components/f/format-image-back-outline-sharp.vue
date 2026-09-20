<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0r6yfb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-back-outline-sharp" /></template>
<style>
.g0r6yfb3g {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h3.75V12.5H4v-1h3.75V8.75H4v-1h16v1h-3.75v2.75H20v1h-3.75v2.75H20v1zm4.75-1h6.5V12.5h-6.5zm0-3.75h6.5V8.75h-6.5zM4 5V4h16v1zm8 6.5");
}

</style>
