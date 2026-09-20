<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p08vtrblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-down-12-regular" /></template>
<style>
.p08vtrblv {
  fill: currentColor;
  d: path("M7.854 5.854a.5.5 0 1 0-.708-.708L6 6.293L4.854 5.146a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0zM11 6A5 5 0 1 0 1 6a5 5 0 0 0 10 0M6 2a4 4 0 1 1 0 8a4 4 0 0 1 0-8");
}

</style>
