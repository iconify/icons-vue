<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i72m-bbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-person-16-filled" /></template>
<style>
.i72m-bbfc {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h3.538A3 3 0 0 1 8 13.5a2.5 2.5 0 0 1 2.273-2.49a3 3 0 0 1-.674-1.243c-.322.469-.826.733-1.599.733c-.897 0-1.432-.356-1.74-.974a2.6 2.6 0 0 1-.228-.718A2 2 0 0 1 6 8.5a.5.5 0 0 0-.5-.5H3V4.5A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5V6h1V4.5A2.5 2.5 0 0 0 11.5 2zm10 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m1.5 4.5c0 1.245-1 2.5-3.5 2.5S9 14.75 9 13.5a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5");
}

</style>
