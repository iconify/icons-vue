<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qpfeooy5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-diagonal-down-left-20-filled" /></template>
<style>
.qpfeooy5w {
  fill: currentColor;
  d: path("M16.854 3.146a.5.5 0 0 1 0 .708L9.707 11H14.5a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 1 0v4.793l7.146-7.147a.5.5 0 0 1 .708 0M5 17a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
