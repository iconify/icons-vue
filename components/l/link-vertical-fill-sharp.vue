<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8dfhgbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-vertical-fill-sharp" /></template>
<style>
.i8dfhgbvx {
  fill: currentColor;
  d: path("M7 9V7a5 5 0 0 1 10 0v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0m6-1v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m-4 7v2a3 3 0 1 0 6 0v-2a1 1 0 0 1 2 0v2a5 5 0 0 1-10 0v-2a1 1 0 0 1 2 0");
}

</style>
