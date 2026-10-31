<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-uod8o9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-16-regular" /></template>
<style>
.n-uod8o9n {
  fill: currentColor;
  d: path("M13.5 11a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S8 13.75 8 12.5A1.5 1.5 0 0 1 9.5 11zM7.731 1.078a.5.5 0 0 1 .538 0l5.093 3.242a1.37 1.37 0 0 1 .475 1.802c-.26-.323-.676-.744-1.012-.958L8 2.093L3.463 4.979a1 1 0 0 0-.46.76l4.994 2.692l.509-.278v.006c.02.357.1.697.232 1.01l-.502.271a.5.5 0 0 1-.473 0L3 6.874V11a1 1 0 0 0 1 1h3.05a2.5 2.5 0 0 0-.05.5q0 .25.038.5H4a2 2 0 0 1-2-2V5.823a2 2 0 0 1 .926-1.687zM11.5 6a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
