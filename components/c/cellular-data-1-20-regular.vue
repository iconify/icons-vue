<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kw_432bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-1-20-regular" /></template>
<style>
.kw_432bky {
  fill: currentColor;
  d: path("M16.503 4a.5.5 0 0 1 .492.41l.008.09v11a.5.5 0 0 1-.992.09l-.008-.09v-11a.5.5 0 0 1 .5-.5m-9 5.999a.5.5 0 0 1 .492.41l.008.09v5a.5.5 0 0 1-.992.09l-.008-.09v-5a.5.5 0 0 1 .5-.5m-3.003 2a.5.5 0 0 1 .492.41L5 12.5v3a.5.5 0 0 1-.992.09L4 15.5v-3a.5.5 0 0 1 .5-.5m6-4.002a.5.5 0 0 1 .492.41l.008.09V15.5a.5.5 0 0 1-.992.09L10 15.5V8.497a.5.5 0 0 1 .5-.5M13.5 6a.5.5 0 0 1 .492.41L14 6.5v9a.5.5 0 0 1-.992.09L13 15.5V6.501a.5.5 0 0 1 .5-.5");
}

</style>
