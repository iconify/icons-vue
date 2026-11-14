<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1qilcc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:community-notice" /></template>
<style>
.v1qilcc3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 2.25H4.25q-2.5 0-2.5 2.5v9.5q0 2.5 2.5 2.5h1v4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.75h10.5v4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.75h1q1.036 0 1.768-.732t.732-1.768v-9.5q0-1.036-.732-1.768T19.75 2.25M7 4.75h3.5q2.25 0 2.25 2.25v5q0 2.25-2.25 2.25H7q-2.25 0-2.25-2.25V7q0-2.25 2.25-2.25m9 1.5h1q2.25 0 2.25 2.25V10q0 2.25-2.25 2.25h-1q-2.25 0-2.25-2.25V8.5q0-2.25 2.25-2.25");
}

</style>
