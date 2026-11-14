<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzeuhdc7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:finish-to-finish" /></template>
<style>
.qzeuhdc7w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25h9q1.036 0 1.768.732q.548.549.686 1.268H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v12q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.296q-.138.719-.686 1.268q-.732.732-1.768.732h-4q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5h4q1.036 0 1.768.732q.548.549.686 1.268h3.546V6.75h-3.546q-.138.719-.686 1.268q-.732.732-1.768.732h-9q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5");
}

</style>
