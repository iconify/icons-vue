<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2kiyd6kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circles-overlap" /></template>
<style>
.w2kiyd6kj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.873 4.373Q1.75 6.497 1.75 9.5t2.123 5.127q1.787 1.786 4.196 2.07q.504 1.629 1.804 2.93Q11.997 21.75 15 21.75t5.127-2.123T22.25 14.5t-2.123-5.127q-1.787-1.786-4.196-2.07q-.504-1.629-1.804-2.93Q12.003 2.25 9 2.25T3.873 4.373");
}

</style>
