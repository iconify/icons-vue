<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7fxi9btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-fill" /></template>
<style>
.t7fxi9btd {
  fill: currentColor;
  d: path("M17 5a3 3 0 0 1 3 3v7.171a3 3 0 1 1-2 0V8a1 1 0 0 0-1-1h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L13.414 5ZM6 8.829v6.342a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2 0");
}

</style>
