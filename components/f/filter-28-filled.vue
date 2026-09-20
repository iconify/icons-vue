<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s1huxebki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-28-filled" /></template>
<style>
.s1huxebki {
  fill: currentColor;
  d: path("M17 19a1 1 0 1 1 0 2h-6a1 1 0 1 1 0-2zm4-6a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zm3-6a1 1 0 1 1 0 2H4a1 1 0 0 1 0-2z");
}

</style>
