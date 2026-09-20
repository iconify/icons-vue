<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7iyexbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-20-filled" /></template>
<style>
.u7iyexbeh {
  fill: currentColor;
  d: path("M7.877 1.879a3 3 0 0 1 4.242 0l6 5.999a3 3 0 0 1 0 4.242l-6 5.999a3 3 0 0 1-4.242 0L1.878 12.12a3 3 0 0 1 0-4.242z");
}

</style>
