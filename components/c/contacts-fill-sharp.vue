<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzr9fxdhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:contacts-fill-sharp" /></template>
<style>
.bzr9fxdhr {
  fill: currentColor;
  d: path("M19 22H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v4h1a1 1 0 0 1 0 2h-1v6h1a1 1 0 0 1 0 2h-1v4a1 1 0 0 1-1 1M8 10a4 4 0 1 0 8 0a4 4 0 0 0-8 0m8.901 10a5.003 5.003 0 0 0-9.802 0Z");
}

</style>
