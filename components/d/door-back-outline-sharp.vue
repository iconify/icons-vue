<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlz71bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-back-outline-sharp" /></template>
<style>
.wtlz71bmo {
  fill: currentColor;
  d: path("M4 20v-1h2V4h12v15h2v1zm3-1h10V5H7zm2.77-6.23q.309 0 .539-.23t.23-.54t-.23-.54t-.54-.23t-.54.23T9 12t.23.54t.54.23M7 5v14z");
}

</style>
