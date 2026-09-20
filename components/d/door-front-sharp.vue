<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1t5p3bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-front-sharp" /></template>
<style>
.g1t5p3bvm {
  fill: currentColor;
  d: path("M4 20h16v-1h-2V4H6v15H4zm9.691-7.46q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23T15 12t-.23.54t-.54.23t-.539-.23");
}

</style>
