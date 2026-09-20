<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1nz0bs0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-48-regular" /></template>
<style>
.v1nz0bs0w {
  fill: currentColor;
  d: path("M31.884 8.366a1.25 1.25 0 0 1 0 1.768L18.018 24l13.866 13.866a1.25 1.25 0 0 1-1.768 1.768l-14.75-14.75a1.25 1.25 0 0 1 0-1.768l14.75-14.75a1.25 1.25 0 0 1 1.768 0");
}

</style>
