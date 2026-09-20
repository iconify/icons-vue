<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i5idx6h8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:leaf-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i5idx6h8i {
  d: path("M11.037 3.048a1.75 1.75 0 0 1 2.2.225l3.712 3.711a6.999 6.999 0 0 1-4.2 11.908v2.358a.75.75 0 0 1-1.5 0v-2.358A6.999 6.999 0 0 1 7.05 6.985l3.712-3.712a1.76 1.76 0 0 1 .275-.225zM12 11a.75.75 0 0 0-.75.75v5.63a5.532 5.532 0 0 0 1.5 0v-5.63A.75.75 0 0 0 12 11z");
  fill: currentColor;
}

</style>
