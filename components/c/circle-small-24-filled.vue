<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwuekqkoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-small-24-filled" /></template>
<style>
.fwuekqkoy {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
