<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="v0vgdxxyh"/><path class="jd0mv8v5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cinema" /></template>
<style>
.jd0mv8v5t {
  fill: var(--svg-color--fff, #fff);
  d: path("M30 20a4 4 0 0 0-4-4H15a4 4 0 0 0-4 4l-6-4H4v13h1l6-4v2a4 4 0 0 0 4 4h11a4 4 0 0 0 4-4z");
}

.v0vgdxxyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 11a6 6 0 1 1-12 0a6 6 0 0 1 12 0m10.999 2a5 5 0 1 1-10.001-.001A5 5 0 0 1 31.999 13");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
