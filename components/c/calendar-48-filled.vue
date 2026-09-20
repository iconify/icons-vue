<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_343accs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-48-filled" /></template>
<style>
.a_343accs {
  fill: currentColor;
  d: path("M6 12.25A6.25 6.25 0 0 1 12.25 6h23.5A6.25 6.25 0 0 1 42 12.25V14H6zm0 4.25v19.25A6.25 6.25 0 0 0 12.25 42h23.5A6.25 6.25 0 0 0 42 35.75V16.5zm12 7a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m6 2.5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5m11-2.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0M15.5 34a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5m11-2.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0");
}

</style>
