<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isr_o-b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ebook-lock" /></template>
<style>
.isr_o-b2d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 17V5q0-1.346.952-2.298T7 1.75h11.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v10.638Q18.694 13 18 13q-.127 0-.25.005V3.25H7q-.725 0-1.237.513Q5.25 4.275 5.25 5v9.084q.708-.334 1.75-.334h8.51q-.637.549-.872 1.5H7q-1.75 0-1.75 1.75T7 18.75h6.018q-.018.241-.018.5v.5q0 .256.03.499l-.03.001H7q-3.25 0-3.25-3.25m17.268.482q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
