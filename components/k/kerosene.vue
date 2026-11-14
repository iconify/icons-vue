<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3lvtwbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kerosene" /></template>
<style>
.k3lvtwbqv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.409 9.481q1.841.651 1.841 3.144v5.75q0 3.375-3.375 3.375h-7.25q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-5.75q0-2.598 2-3.196V7.5q0-1.75 1.75-1.75h3q1.75 0 1.75 1.75v1.75h1.899l4.775-5.73q.107-.128.258-.199T18 3.25h2.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.149zM9.25 9.25h-3.5V7.5q0-.25.25-.25h3q.25 0 .25.25zm11.342-1.71Q22.5 9.993 22.5 11.25q0 2.5-2.5 2.5t-2.5-2.5q0-1.257 1.908-3.71q.092-.118.221-.192q.13-.074.278-.092t.292.021t.261.131q.074.058.132.132");
}

</style>
