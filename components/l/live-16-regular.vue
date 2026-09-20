<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hisp8dqdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-16-regular" /></template>
<style>
.hisp8dqdy {
  fill: currentColor;
  d: path("M3.051 3.05a.5.5 0 0 1 .707.707a6 6 0 0 0 0 8.485a.501.501 0 0 1-.707.708a7 7 0 0 1 0-9.9m9.193 0a.5.5 0 0 1 .707 0a7 7 0 0 1 0 9.9a.5.5 0 0 1-.707-.708a6 6 0 0 0 0-8.485a.5.5 0 0 1 0-.707M4.819 4.818a.5.5 0 1 1 .707.707a3.5 3.5 0 0 0 0 4.95a.5.5 0 0 1-.707.707a4.5 4.5 0 0 1 0-6.364m5.656 0a.5.5 0 0 1 .707 0a4.5 4.5 0 0 1 0 6.364a.5.5 0 0 1-.707-.707a3.5 3.5 0 0 0 0-4.95a.5.5 0 0 1 0-.707M8 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
