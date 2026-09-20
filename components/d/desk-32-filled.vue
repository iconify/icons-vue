<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nm6v3_bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-32-filled" /></template>
<style>
.nm6v3_bem {
  fill: currentColor;
  d: path("M16 24.75A3.25 3.25 0 0 1 12.75 28h-7.5A3.25 3.25 0 0 1 2 24.75V12h14zM26.75 4A3.25 3.25 0 0 1 30 7.25V27a1 1 0 1 1-2 0V10H2V7.25A3.25 3.25 0 0 1 5.25 4zM7 16a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2z");
}

</style>
