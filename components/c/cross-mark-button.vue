<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u5zlojb3x"/><path class="vzl6nybtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cross-mark-button" /></template>
<style>
.u5zlojb3x {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.vzl6nybtn {
  fill: var(--svg-color--fff, #fff);
  d: path("m21.529 18.006l8.238-8.238a2.5 2.5 0 0 0 0-3.535a2.5 2.5 0 0 0-3.535 0l-8.238 8.238l-8.238-8.238a2.5 2.5 0 0 0-3.535 0a2.5 2.5 0 0 0 0 3.535l8.238 8.238l-8.258 8.258a2.498 2.498 0 0 0 1.768 4.267c.64 0 1.28-.244 1.768-.732l8.258-8.259l8.238 8.238c.488.488 1.128.732 1.768.732s1.279-.244 1.768-.732a2.5 2.5 0 0 0 0-3.535z");
}

</style>
