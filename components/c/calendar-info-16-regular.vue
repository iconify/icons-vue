<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kyu56s02l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-info-16-regular" /></template>
<style>
.kyu56s02l {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v2.1a5.5 5.5 0 0 0-1-.393V6H3v5.5A1.5 1.5 0 0 0 4.5 13h1.707q.149.524.393 1H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm0 1h-7A1.5 1.5 0 0 0 3 4.5V5h10v-.5A1.5 1.5 0 0 0 11.5 3m-.625 6.5a.625.625 0 1 1 1.25 0a.625.625 0 0 1-1.25 0m1.125 4a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 1 0zm-5-2a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0m8 0a3.5 3.5 0 1 0-7 0a3.5 3.5 0 0 0 7 0");
}

</style>
