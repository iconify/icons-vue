<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwa4r6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hangout-video-off-sharp" /></template>
<style>
.pwa4r6bbl {
  fill: currentColor;
  d: path("M20.5 23.3L17.15 20H2V4h2l.6.6v2.8L.7 3.5l1.4-1.4l19.8 19.8zm1.5-4.15l-4-4V8l-4 3.15v-3.1h-3.1L6.85 4H22zM6 16h7.15L6 8.85z");
}

</style>
