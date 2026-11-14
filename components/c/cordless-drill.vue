<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gorzs0b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cordless-drill" /></template>
<style>
.gorzs0b4v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75h6q1.76 0 3.005 1.245q.27.27.482.564q.477-.309 1.263-.309q2 0 2 2h2.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.25q0 2-2 2q-.786 0-1.263-.309q-.212.294-.482.564Q14.26 11.25 12.5 11.25h-.815l-.364 4.008q2.929.156 2.929 3.242q0 1.346-.952 2.298T11 21.75H6q-1.346 0-2.298-.952T2.75 18.5q0-2.885 2.561-3.209l.374-4.113q-1.244-.227-2.19-1.173Q2.25 8.76 2.25 7t1.245-3.005T6.5 2.75m.685 8.5l-.364 4h2.994l.364-4z");
}

</style>
