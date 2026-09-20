<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j6m1oknyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-right-12-filled" /></template>
<style>
.j6m1oknyf {
  fill: currentColor;
  d: path("M1 6a.5.5 0 0 1 .5-.5h3.793L4.146 4.354a.5.5 0 1 1 .708-.708l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 1 1-.708-.708L5.293 6.5H1.5A.5.5 0 0 1 1 6m10 0a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0");
}

</style>
