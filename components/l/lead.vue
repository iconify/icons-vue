<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcgaabcah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead" /></template>
<style>
.fcgaabcah {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 7.25q0-2.071 1.464-3.536Q9.929 2.25 12 2.25t3.536 1.464Q17 5.179 17 7.25t-1.464 3.536T12 12.25t-3.536-1.464Q7 9.321 7 7.25m-1.116 7.947Q3.25 17.029 3.25 20q0 1.75 1.75 1.75h14q1.75 0 1.75-1.75q0-2.971-2.634-4.803Q15.677 13.5 12 13.5t-6.116 1.697");
}

</style>
