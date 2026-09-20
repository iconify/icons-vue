<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfjw8t5mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hangout-video-off-outline-sharp" /></template>
<style>
.nfjw8t5mi {
  fill: currentColor;
  d: path("M10.9 8.05H14v3.1zm3.1 3.1L18 8v7.15zm6 6l2 2V4H6.85l2 2H20zM4 4l2 2H4v12h11.15l-2-2H6V8.85L.7 3.5l1.4-1.4l19.8 19.8l-1.4 1.4l-3.35-3.3H2V4zm5.6 8.45");
}

</style>
