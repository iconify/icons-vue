<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru2dtsixs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frame-fill" /></template>
<style>
.ru2dtsixs {
  fill: currentColor;
  d: path("M8 6h8V3a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2h-3v8h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-3H8v3a1 1 0 0 1-2 0v-3H3a1 1 0 0 1 0-2h3V8H3a1 1 0 0 1 0-2h3V3a1 1 0 0 1 2 0Z");
}

</style>
