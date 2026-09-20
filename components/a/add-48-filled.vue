<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8bd4cc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-48-filled" /></template>
<style>
.o8bd4cc2e {
  fill: currentColor;
  d: path("M24 5a1.5 1.5 0 0 1 1.5 1.5v16h16a1.5 1.5 0 0 1 0 3h-16v16a1.5 1.5 0 0 1-3 0v-16h-16a1.5 1.5 0 0 1 0-3h16v-16A1.5 1.5 0 0 1 24 5");
}

</style>
