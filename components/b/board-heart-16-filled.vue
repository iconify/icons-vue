<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="scui3p59y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-heart-16-filled" /></template>
<style>
.scui3p59y {
  fill: currentColor;
  d: path("M7.5 2v3H2v-.5A2.5 2.5 0 0 1 4.5 2zm1 0v4a3.54 3.54 0 0 1 2 .574a3.55 3.55 0 0 1 3.5-.212V4.5A2.5 2.5 0 0 0 11.5 2zm-1 4v.163a3.55 3.55 0 0 0-1.459.89a3.597 3.597 0 0 0 0 5.062l1.459 1.47V14h-3A2.5 2.5 0 0 1 2 11.5V6zm-.749 5.41l3.43 3.457a.45.45 0 0 0 .637 0l3.431-3.457A2.598 2.598 0 0 0 14 7.536a2.55 2.55 0 0 0-3.377.22l-.123.124l-.123-.123l-.075-.073A2.545 2.545 0 0 0 7.5 7.232a2.597 2.597 0 0 0-.749 4.178");
}

</style>
