<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt5bygb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-break-left-outline" /></template>
<style>
.gt5bygb6f {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-8.5h8.5v8.5zm1-1h6.5v-6.5H5zM4 5V4h16v1zm4.25 7");
}

</style>
