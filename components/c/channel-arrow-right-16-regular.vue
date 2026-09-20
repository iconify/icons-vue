<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f6i0aeb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-16-regular" /></template>
<style>
.f6i0aeb3i {
  fill: currentColor;
  d: path("M10.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m.354 2.146a.5.5 0 1 0-.707.708L11.293 10H8.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.503.503 0 0 0-.002-.706zM2.5 8a1 1 0 0 0 1 1h1.707a5.5 5.5 0 0 0-.185 1H3.5a2 2 0 0 1-2-2V5.678a1.75 1.75 0 0 0 1 0zM6 6a.5.5 0 0 1 0 1H4.5a.5.5 0 0 1 0-1zm2.5-5a2 2 0 0 1 2 2v2q-.513 0-1 .09V3a1 1 0 0 0-1-1h-5a1 1 0 0 0-.798.396A1.74 1.74 0 0 0 1.63 2.29A2 2 0 0 1 3.5 1zm-1 3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zM2 3.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
