<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="acrho42aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:behance-logo" /></template>
<style>
.acrho42aw {
  fill: currentColor;
  d: path("M160 80a8 8 0 0 1 8-8h64a8 8 0 0 1 0 16h-64a8 8 0 0 1-8-8m-24 78a42 42 0 0 1-42 42H32a8 8 0 0 1-8-8V64a8 8 0 0 1 8-8h58a38 38 0 0 1 25.65 66A42 42 0 0 1 136 158m-96-42h50a22 22 0 0 0 0-44H40Zm80 42a26 26 0 0 0-26-26H40v52h54a26 26 0 0 0 26-26m128-6a8 8 0 0 1-8 8h-71a32 32 0 0 0 56.59 11.2a8 8 0 0 1 12.8 9.61A48 48 0 1 1 248 152m-17-8a32 32 0 0 0-62 0Z");
}

</style>
