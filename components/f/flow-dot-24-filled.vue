<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds7_2acvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-dot-24-filled" /></template>
<style>
.ds7_2acvs {
  fill: currentColor;
  d: path("M5.5 2.5c1.025 0 1.904.617 2.29 1.5h8.71a4.5 4.5 0 1 1 0 9h-9a2.5 2.5 0 0 0 0 5h8.71A2.499 2.499 0 0 1 21 19a2.5 2.5 0 0 1-4.79 1H7.5a4.5 4.5 0 1 1 0-9h9a2.5 2.5 0 0 0 0-5H7.79A2.499 2.499 0 1 1 5.5 2.5");
}

</style>
