<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqoapcb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-48-filled" /></template>
<style>
.gqoapcb6h {
  fill: currentColor;
  d: path("M17 27.75A8.25 8.25 0 0 0 25.25 36h3.744a6.25 6.25 0 0 1-6.244 6h-10.5A6.25 6.25 0 0 1 6 35.75v-15.5A6.25 6.25 0 0 1 12.25 14H17zM35.75 6A6.25 6.25 0 0 1 42 12.25v15.5A6.25 6.25 0 0 1 35.75 34h-10.5A6.25 6.25 0 0 1 19 27.75v-15.5A6.25 6.25 0 0 1 25.25 6z");
}

</style>
