<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ic43zzb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-16-filled" /></template>
<style>
.ic43zzb0h {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 9a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-5.5a.5.5 0 0 0-.5.5v3.5l.008.09A.5.5 0 0 0 8.5 8.5V5l-.008-.09A.5.5 0 0 0 8 4.5");
}

</style>
