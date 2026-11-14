<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4nmdlmil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-blindness-sim" /></template>
<style>
.d4nmdlmil {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.125q-7.8 0-10.215 7.649q-.072.226 0 .452Q4.2 19.875 12 19.875t10.215-7.649q.072-.226 0-.452Q19.8 4.125 12 4.125M12 7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T12 17q-2.071 0-3.536-1.464Q7 14.071 7 12t1.464-3.536T12 7");
}

</style>
