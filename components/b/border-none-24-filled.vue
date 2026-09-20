<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i30i7ubgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-none-24-filled" /></template>
<style>
.i30i7ubgi {
  fill: currentColor;
  d: path("M14 4a1 1 0 0 1-1 1h-2a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1m-9 7a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0zm14 0a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zm-6 10a1 1 0 1 0 0-2h-2a1 1 0 1 0 0 2zM7 4a1 1 0 0 0-1-1a3 3 0 0 0-3 3a1 1 0 0 0 2 0a1 1 0 0 1 1-1a1 1 0 0 0 1-1m11-1a1 1 0 1 0 0 2a1 1 0 0 1 1 1a1 1 0 1 0 2 0a3 3 0 0 0-3-3M7 20a1 1 0 0 1-1 1a3 3 0 0 1-3-3a1 1 0 1 1 2 0a1 1 0 0 0 1 1a1 1 0 0 1 1 1m11 1a1 1 0 1 1 0-2a1 1 0 0 0 1-1a1 1 0 1 1 2 0a3 3 0 0 1-3 3");
}

</style>
