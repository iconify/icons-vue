<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-1j5zpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-24-regular" /></template>
<style>
.f0-1j5zpn {
  fill: currentColor;
  d: path("M10 9a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2zm2-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V9a.5.5 0 0 0-.5-.5zM4 4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm16 1.5a.5.5 0 0 1 .5.5v12a.5.5 0 0 1-.5.5H7.5v-13zm-16 0h2v13H4a.5.5 0 0 1-.5-.5V6a.5.5 0 0 1 .5-.5");
}

</style>
