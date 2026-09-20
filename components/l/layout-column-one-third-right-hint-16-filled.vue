<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q04d93j3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-one-third-right-hint-16-filled" /></template>
<style>
.q04d93j3u {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5a.5.5 0 0 0 1 0A1.5 1.5 0 0 1 4.5 3a.5.5 0 0 0 0-1M7 2a.5.5 0 0 0 0 1h1.5a.5.5 0 0 0 0-1zM3 7a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm0 4.5a.5.5 0 0 0-1 0A2.5 2.5 0 0 0 4.5 14a.5.5 0 0 0 0-1A1.5 1.5 0 0 1 3 11.5M7 13a.5.5 0 0 0 0 1h1.5a.5.5 0 0 0 0-1zm3-10.5a.5.5 0 0 1 .5-.5h1A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-1a.5.5 0 0 1-.5-.5z");
}

</style>
