<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rtd-z_9gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-left-12-regular" /></template>
<style>
.rtd-z_9gn {
  fill: currentColor;
  d: path("M6.146 7.854a.5.5 0 1 0 .708-.708L5.707 6l1.147-1.146a.5.5 0 1 0-.708-.708l-1.5 1.5a.5.5 0 0 0 0 .708zM6 11A5 5 0 1 0 6 1a5 5 0 0 0 0 10m4-5a4 4 0 1 1-8 0a4 4 0 0 1 8 0");
}

</style>
