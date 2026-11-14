<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3h1o7-8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:input-field-focused" /></template>
<style>
.i3h1o7-8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 4.25h6q3.21 0 5.48 2.27T22.75 12t-2.27 5.48T15 19.75H9q-3.21 0-5.48-2.27T1.25 12t2.27-5.48T9 4.25M7.375 7Q4 7 4 10.375v3.25q0 1.398.989 2.386q.988.989 2.386.989h9.25Q20 17 20 13.625v-3.25Q20 7 16.625 7zm0 1.5q-.777 0-1.326.549T5.5 10.375v3.25q0 1.875 1.875 1.875h9.25q1.875 0 1.875-1.875v-3.25q0-1.875-1.875-1.875zm.375 5.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7 10.5v3q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014");
}

</style>
