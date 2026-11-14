<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-tm6tb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fixer-bottle" /></template>
<style>
.u-tm6tb0u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.25h4q2.25 0 2.25 2.25v1q0 .556-.235 1.015q.82.31 1.49.98q.573.573.882 1.255H18.5q2.75 0 2.75 2.75V14q0 2.75-2.75 2.75h-.75V18q0 1.76-1.245 3.005T13.5 22.25h-5q-1.76 0-3.005-1.245T4.25 18v-7.5q0-1.76 1.245-3.005q.67-.67 1.49-.98Q6.75 6.056 6.75 5.5v-1q0-2.25 2.25-2.25m8.75 13h.75q1.25 0 1.25-1.25v-2.5q0-1.25-1.25-1.25h-.756q.006.124.006.25zm-3.5-2.5h-6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7 13.5t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T15 13.5t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
