<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvk0bla4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-right-fill-round" /></template>
<style>
.mvk0bla4o {
  fill: currentColor;
  d: path("M14.707 11.293a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 9 16V8a1.002 1.002 0 0 1 1.707-.707Z");
}

</style>
