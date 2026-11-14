<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4v-g-5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-24-regular" /></template>
<style>
.dj4v-g-5e {
  fill: currentColor;
  d: path("M21.25 18.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm0-5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm0-5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm0-5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5z");
}

</style>
