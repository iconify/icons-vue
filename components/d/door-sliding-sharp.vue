<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpnt34b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sliding-sharp" /></template>
<style>
.gpnt34b1b {
  fill: currentColor;
  d: path("M10.27 12.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.54-.23m4.538 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.229.54t.23.54t.54.23t.539-.23M4.5 20v-1h1V4h6.116v15h.769V4H18.5v15h1v1z");
}

</style>
