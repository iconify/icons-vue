<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxp6fdcrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-arrow-right-16-regular" /></template>
<style>
.xxp6fdcrr {
  fill: currentColor;
  d: path("M5 6a3 3 0 0 1 5.833-.99a5.5 5.5 0 0 1 1.084.174a4.001 4.001 0 0 0-7.887.323A3.25 3.25 0 0 0 4.25 12h.957a5.5 5.5 0 0 1-.185-1H4.25a2.25 2.25 0 0 1 0-4.5h.25A.5.5 0 0 0 5 6m5.5 0a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.353 4.854l.003-.003a.5.5 0 0 0 .144-.348v-.006a.5.5 0 0 0-.146-.35l-2-2a.5.5 0 0 0-.708.707L11.293 10H8.5a.5.5 0 0 0 0 1h2.793l-1.147 1.146a.5.5 0 0 0 .708.708z");
}

</style>
