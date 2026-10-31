<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nc0g8aceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-48-filled" /></template>
<style>
.nc0g8aceb {
  fill: currentColor;
  d: path("M17 27.75A8.25 8.25 0 0 0 25.25 36H29v1.75A6.25 6.25 0 0 1 22.75 44h-12.5A6.25 6.25 0 0 1 4 37.75v-17.5A6.25 6.25 0 0 1 10.25 14H17zM37.75 4A6.25 6.25 0 0 1 44 10.25v17.5A6.25 6.25 0 0 1 37.75 34h-12.5A6.25 6.25 0 0 1 19 27.75v-17.5A6.25 6.25 0 0 1 25.25 4z");
}

</style>
