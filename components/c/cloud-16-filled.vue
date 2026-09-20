<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t8sdbab6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-16-filled" /></template>
<style>
.t8sdbab6k {
  fill: currentColor;
  d: path("M4.03 5.507a4 4 0 0 1 7.94 0A3.25 3.25 0 0 1 11.75 12h-7.5a3.25 3.25 0 0 1-.22-6.493");
}

</style>
