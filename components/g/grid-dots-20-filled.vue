<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c-v9vibjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-dots-20-filled" /></template>
<style>
.c-v9vibjs {
  fill: currentColor;
  d: path("M4.25 14a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5M10 14a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5m5.75 0a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5M4.25 8.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5m5.75 0a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5m5.75 0a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5M4.25 2.5a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5m5.75 0A1.75 1.75 0 1 1 10 6a1.75 1.75 0 0 1 0-3.5m5.75 0a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
