<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_d-ebbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:honesty-box" /></template>
<style>
.b_d-ebbfo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.25Q8.25 4.25 8.25 8T12 11.75T15.75 8T12 4.25m-5.75 4.5H5q-1.25 0-1.25 1.25v3.25h16.5V10q0-1.25-1.25-1.25h-1.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17 8t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H19q2.75 0 2.75 2.75v8.5q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75V10q0-2.75 2.75-2.75h1.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T7 8t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-2.5 6v3.75q0 1.25 1.25 1.25h14q1.25 0 1.25-1.25v-3.75z");
}

</style>
