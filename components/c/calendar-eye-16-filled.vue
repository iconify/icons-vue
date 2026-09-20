<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ej9-psb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-16-filled" /></template>
<style>
.ej9-psb2w {
  fill: currentColor;
  d: path("M11.5 8c2.761 0 4.5 2.3 4.5 3.5c0 1.182-1.739 3.5-4.5 3.5S7 12.7 7 11.5C7 10.318 8.736 8 11.5 8m2.5-.434a5.79 5.79 0 0 0-6.469 1.009a5.5 5.5 0 0 0-1.097 1.406C6.18 10.451 6 10.983 6 11.5c0 .822.45 1.739 1.116 2.5H4.5A2.5 2.5 0 0 1 2 11.5V6h12zM12.457 9.19a2.501 2.501 0 1 0-1.915 4.622a2.501 2.501 0 0 0 1.915-4.622M11.5 10a1.5 1.5 0 1 1 0 2.999a1.5 1.5 0 0 1 0-2.999m0-8A2.5 2.5 0 0 1 14 4.5V5H2v-.5A2.5 2.5 0 0 1 4.5 2z");
}

</style>
