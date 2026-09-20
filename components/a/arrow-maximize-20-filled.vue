<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l36w5njqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-20-filled" /></template>
<style>
.l36w5njqm {
  fill: currentColor;
  d: path("M15.75 3.5a.75.75 0 0 1 .75.75v6a.75.75 0 0 1-1.5 0V6.06L6.06 15h4.19a.75.75 0 0 1 0 1.5h-6a.75.75 0 0 1-.75-.75v-6a.75.75 0 0 1 1.5 0v4.19L13.94 5H9.75a.75.75 0 0 1 0-1.5z");
}

</style>
