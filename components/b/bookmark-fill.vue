<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w3fj767zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bookmark-fill" /></template>
<style>
.w3fj767zs {
  fill: currentColor;
  d: path("M184 32H72a16 16 0 0 0-16 16v176a8 8 0 0 0 12.24 6.78L128 193.43l59.77 37.35A8 8 0 0 0 200 224V48a16 16 0 0 0-16-16m-51.77 145.22a8 8 0 0 0-8.48 0L72 209.57v-29.14l56-35l56 35v29.14Z");
}

</style>
