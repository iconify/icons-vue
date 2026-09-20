<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xd537gheq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-28-filled" /></template>
<style>
.xd537gheq {
  fill: currentColor;
  d: path("M15 4a1 1 0 1 0-2 0v13.586l-4.293-4.293a1 1 0 0 0-1.414 1.414l6 6a1 1 0 0 0 1.414 0l6-6a1 1 0 0 0-1.414-1.414L15 17.586zM6 23a1 1 0 1 0 0 2h16a1 1 0 1 0 0-2z");
}

</style>
