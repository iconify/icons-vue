<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwc6tdbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-undo-20-filled" /></template>
<style>
.nwc6tdbke {
  fill: currentColor;
  d: path("M6.862 6.5H9.25a.75.75 0 0 1 0 1.5h-4.4A.85.85 0 0 1 4 7.15v-4.4a.75.75 0 0 1 1.5 0v2.947l3.059-2.66a5.25 5.25 0 0 1 6.888 7.925l-8.172 7.104a.75.75 0 1 1-.984-1.132l8.172-7.104a3.75 3.75 0 1 0-4.92-5.66z");
}

</style>
