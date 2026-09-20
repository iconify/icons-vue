<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw50fhd4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-surprise-24-regular" /></template>
<style>
.yw50fhd4e {
  fill: currentColor;
  d: path("M12 2.004c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10s4.477-10 10-10m0 1.5a8.5 8.5 0 1 0 0 17a8.5 8.5 0 0 0 0-17m0 9.495a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 0 1 0-4.5M9 8.75a1.25 1.25 0 1 1 0 2.499A1.25 1.25 0 0 1 9 8.75m6 0a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.499");
}

</style>
