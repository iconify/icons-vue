<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxlmojdxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:label-fill-sharp" /></template>
<style>
.kxlmojdxs {
  fill: currentColor;
  d: path("M14 5c.265 0 .52.105.707.293l6 6a1 1 0 0 1 0 1.414l-6 6A1 1 0 0 1 14 19H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Z");
}

</style>
