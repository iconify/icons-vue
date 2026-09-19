<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fujsstjml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coverflex" /></template>
<style>
.fujsstjml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.819c-10.77 0-19.5 8.73-19.5 19.5q0 .431.019.862l38.975-.313q.006-.274.006-.55c0-10.769-8.73-19.499-19.5-19.5Z");
}

</style>
