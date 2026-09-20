<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ilk3n6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:church" /></template>
<style>
.e5ilk3n6t {
  fill: currentColor;
  d: path("M2 22v-8l4-1.775V9l5-2.5V5H9V3h2V1h2v2h2v2h-2v1.5L18 9v3.225L22 14v8h-8v-3q0-.825-.587-1.412T12 17t-1.412.588T10 19v3zm11.063-8.937q.437-.438.437-1.063t-.437-1.062T12 10.5t-1.062.438T10.5 12t.438 1.063T12 13.5t1.063-.437");
}

</style>
