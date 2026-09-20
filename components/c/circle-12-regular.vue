<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e9gj4rbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-12-regular" /></template>
<style>
.e9gj4rbys {
  fill: currentColor;
  d: path("M6 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6");
}

</style>
