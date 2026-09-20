<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtwu7jbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-48-filled" /></template>
<style>
.vtwu7jbzq {
  fill: currentColor;
  d: path("M8.44 15.94a1.5 1.5 0 0 1 2.12 0L24 29.378l13.44-13.44a1.5 1.5 0 0 1 2.12 2.122l-14.5 14.5a1.5 1.5 0 0 1-2.12 0l-14.5-14.5a1.5 1.5 0 0 1 0-2.122");
}

</style>
