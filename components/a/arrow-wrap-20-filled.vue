<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wwxlsr2ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-wrap-20-filled" /></template>
<style>
.wwxlsr2ob {
  fill: currentColor;
  d: path("M13.75 3.5a3.25 3.25 0 0 1 0 6.5h-7.5a1.75 1.75 0 1 0 0 3.5h9.19l-.22-.22a.75.75 0 1 1 1.06-1.06l1.5 1.5a.75.75 0 0 1 0 1.06l-1.5 1.5a.75.75 0 1 1-1.06-1.06l.22-.22H6.25a3.25 3.25 0 0 1 0-6.5h7.5a1.75 1.75 0 1 0 0-3.5h-10a.75.75 0 0 1 0-1.5z");
}

</style>
