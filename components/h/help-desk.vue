<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt9bl8bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:help-desk" /></template>
<style>
.vt9bl8bzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10.25v1.542q-.374.193-.695.513q-.805.806-.805 1.945v2Q2.25 19 5 19t2.75-2.75v-2q0-2.622-2.5-2.744V10.25q0-2.796 1.977-4.773T12 3.5t4.773 1.977t1.977 4.773v1.256q-2.5.122-2.5 2.744v2q0 2.342 1.995 2.689Q18.153 20.5 16.5 20.5H13q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T13 22h3.5q3.153 0 3.247-3.059q2.003-.344 2.003-2.691v-2q0-2.031-1.5-2.562V10.25q0-3.417-2.416-5.834T12 2T6.166 4.416Q3.75 6.833 3.75 10.25");
}

</style>
