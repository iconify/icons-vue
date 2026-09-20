<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryw4k4ybv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sliding-outline-sharp" /></template>
<style>
.ryw4k4ybv {
  fill: currentColor;
  d: path("M9.191 12.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.229.54t-.23.54t-.54.23t-.539-.23m4.539 0q-.23-.23-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23t-.54-.23M4.5 20v-1h1V4h13v15h1v1zm2-1h5V5h-5zm6 0h5V5h-5zm-.5-7.5");
}

</style>
