<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g9y33gb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-12-regular" /></template>
<style>
.g9y33gb7m {
  fill: currentColor;
  d: path("M2.146 7.354a.5.5 0 0 0 .708 0L6 4.207l3.146 3.147a.5.5 0 1 0 .708-.708l-3.5-3.5a.5.5 0 0 0-.708 0l-3.5 3.5a.5.5 0 0 0 0 .708");
}

</style>
