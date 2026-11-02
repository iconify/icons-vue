<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_-wxsbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-branch-fill-sharp" /></template>
<style>
.b_-wxsbgx {
  fill: currentColor;
  d: path("M6 8.829V11h12V8.829a3 3 0 1 1 2 0V12a1 1 0 0 1-1 1H6v2.171a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2 0");
}

</style>
