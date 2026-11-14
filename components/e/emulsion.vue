<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbiog2bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emulsion" /></template>
<style>
.fbiog2bdb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 14.5q0-4.796-7.202-12.512q-.017-.019-.036-.036q-.109-.102-.249-.154t-.289-.048q-.149.006-.285.067t-.237.171Q4.25 9.704 4.25 14.5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48m-10-4q0-2.25 2.25-2.25t2.25 2.25T12 12.75T9.75 10.5M7 16q0-2.25 2.25-2.25T11.5 16t-2.25 2.25T7 16m7.75-2.25Q17 13.75 17 16t-2.25 2.25T12.5 16t2.25-2.25");
}

</style>
