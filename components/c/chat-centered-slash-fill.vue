<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u-e13qsnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-centered-slash-fill" /></template>
<style>
.u-e13qsnz {
  fill: currentColor;
  d: path("M232 56v128a15.93 15.93 0 0 1-4.82 11.42a4 4 0 0 1-5.68-.25L86.52 46.69a4 4 0 0 1 3-6.69H216a16 16 0 0 1 16 16M53.92 34.62A8 8 0 0 0 40 40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h60.43l13.68 23.94a16 16 0 0 0 27.78 0L155.57 200h27.07l19.44 21.38a8 8 0 1 0 11.84-10.76Z");
}

</style>
