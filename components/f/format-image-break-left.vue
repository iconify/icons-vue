<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjda77cbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-break-left" /></template>
<style>
.yjda77cbe {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-8.5h8.5v8.5zM4 5V4h16v1z");
}

</style>
