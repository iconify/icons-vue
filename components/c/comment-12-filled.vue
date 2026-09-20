<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dwh8do1gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-12-filled" /></template>
<style>
.dwh8do1gg {
  fill: currentColor;
  d: path("M3 1a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2v1.5a.5.5 0 0 0 .777.416L6.651 9H9a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2z");
}

</style>
