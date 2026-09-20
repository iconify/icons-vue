<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l5lu0qbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-3-32-filled" /></template>
<style>
.l5lu0qbei {
  fill: currentColor;
  d: path("M2 6.25C2 5.56 2.56 5 3.25 5h25.5a1.25 1.25 0 1 1 0 2.5H3.25C2.56 7.5 2 6.94 2 6.25m0 10c0-.69.56-1.25 1.25-1.25h25.5a1.25 1.25 0 1 1 0 2.5H3.25c-.69 0-1.25-.56-1.25-1.25M3.25 25a1.25 1.25 0 1 0 0 2.5h25.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
