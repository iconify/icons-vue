<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j85bz6bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-48-regular" /></template>
<style>
.j85bz6bym {
  fill: currentColor;
  d: path("M39.634 31.884a1.25 1.25 0 0 1-1.768 0L24 18.018L10.134 31.884a1.25 1.25 0 0 1-1.768-1.768l14.75-14.75a1.25 1.25 0 0 1 1.768 0l14.75 14.75a1.25 1.25 0 0 1 0 1.768");
}

</style>
