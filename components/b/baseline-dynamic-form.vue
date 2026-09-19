<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6pxkhb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-dynamic-form" /></template>
<style>
.q6pxkhb3l {
  fill: currentColor;
  d: path("M17 20v-9h-2V4h7l-2 5h2zm-2-7v7H4c-1.1 0-2-.9-2-2v-3c0-1.1.9-2 2-2zm-8.75 2.75h-1.5v1.5h1.5zM13 4v7H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2zM6.25 6.75h-1.5v1.5h1.5z");
}

</style>
