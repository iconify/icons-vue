<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4ecn-4-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-right-48-regular" /></template>
<style>
.j4ecn-4-e {
  fill: currentColor;
  d: path("M22.25 42a1.25 1.25 0 1 1 0-2.5h15.482L6.366 8.134a1.25 1.25 0 1 1 1.768-1.768L39.5 37.732V22.25a1.25 1.25 0 0 1 2.5 0v18.5c0 .69-.56 1.25-1.25 1.25z");
}

</style>
