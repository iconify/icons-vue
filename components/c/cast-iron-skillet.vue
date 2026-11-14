<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5c3xib2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cast-iron-skillet" /></template>
<style>
.z5c3xib2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5q0-3.21 2.27-5.48T9.5 3.75t5.48 2.27q2 2 2.238 4.73H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.282q-.238 2.73-2.238 4.73q-2.27 2.27-5.48 2.27t-5.48-2.27t-2.27-5.48m3.5 0q0-1.76 1.245-3.005T9.5 7.25t3.005 1.245T13.75 11.5t-1.245 3.005T9.5 15.75t-3.005-1.245T5.25 11.5");
}

</style>
