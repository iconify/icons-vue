<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qpy5ivb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-1-dashes-16-filled" /></template>
<style>
.qpy5ivb6f {
  fill: currentColor;
  d: path("M2 7.75A.75.75 0 0 1 2.75 7h1.5a.75.75 0 0 1 0 1.5h-1.5A.75.75 0 0 1 2 7.75m4.5 0A.75.75 0 0 1 7.25 7h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75m4.5 0a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75");
}

</style>
