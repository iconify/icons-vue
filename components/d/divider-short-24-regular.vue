<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmazx7dse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:divider-short-24-regular" /></template>
<style>
.rmazx7dse {
  fill: currentColor;
  d: path("M11.25 4.75v14.5a.75.75 0 0 0 1.5 0V4.75a.75.75 0 0 0-1.5 0");
}

</style>
