<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t53kz5bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-off-28-filled" /></template>
<style>
.t53kz5bhs {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L13 14.06v3.526l-4.293-4.293a1 1 0 0 0-1.414 1.414l6 6a1 1 0 0 0 1.414 0l2.47-2.47L21.939 23H6a1 1 0 1 0 0 2h16a1 1 0 0 0 .998-.94l1.721 1.72a.75.75 0 0 0 1.061-1.06zm12.483 14.603l-.763.763V16.06zM13 9.818l2 2V4a1 1 0 1 0-2 0zm6.298 6.298l-1.414-1.414l1.409-1.41a1 1 0 0 1 1.414 1.415z");
}

</style>
