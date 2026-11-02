<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sijnc5bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-fill" /></template>
<style>
.sijnc5bfq {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0v3h2a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3Zm6-3a2 2 0 1 0-4 0v3h4Z");
}

</style>
