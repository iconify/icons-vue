<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsopxpdbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-moped" /></template>
<style>
.gsopxpdbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 5.25h3.5q2.264 0 2.478 2.051q.131-.051.272-.051h4.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.891l-1.875 8.905q-.013.062-.037.122q-.024.059-.057.114t-.076.103t-.091.088q-.05.041-.106.072t-.116.053q-.061.021-.124.032T12 18.25H9.208q-.354 3-3.708 3q-3.75 0-3.75-3.75t3.75-3.75q3.354 0 3.708 3h2.183l1.124-5.337q-.563.337-1.265.337h-3.5q-1.036 0-1.768-.732T5.25 9.25v-1.5q0-2.5 2.5-2.5m7 12.25q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75");
}

</style>
