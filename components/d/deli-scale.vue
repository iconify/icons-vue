<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1t7_cbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deli-scale" /></template>
<style>
.a1t7_cbkm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 4.25h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.015.147q-.787 3.936-9.485 4.096v1.507H17q1.76 0 3.005 1.245T21.25 15v3q0 1.76-1.245 3.005T17 22.25H7q-1.76 0-3.005-1.245T2.75 18v-3q0-1.76 1.245-3.005T7 10.75h4.25V9.243q-8.698-.16-9.485-4.096q-.015-.072-.015-.146t.014-.147q.015-.072.043-.14t.069-.13q.041-.061.093-.114q.052-.052.114-.093q.061-.041.129-.07q.068-.028.141-.042T2.5 4.25m13 9.25h-7q-2.25 0-2.25 2.25v1.5q0 2.25 2.25 2.25h7q2.25 0 2.25-2.25v-1.5q0-2.25-2.25-2.25");
}

</style>
