<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lesq9vb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:homeware-department" /></template>
<style>
.lesq9vb0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 4.75H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v12q0 1.968 1.391 3.359T8 22.25h4q1.968 0 3.359-1.391T16.75 17.5v-1.75h.75q3.75 0 3.75-3.75T17.5 8.25h-.75V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 4.75m-3.06 6.224q.81.675.81 1.729V14.5q0 2.25-2.25 2.25h-3q-2.25 0-2.25-2.25v-1.797q0-1.054.81-1.729l1.5-1.25q1.44-1.2 2.88 0zm4.56 3.276h-.75v-4.5h.75q2.25 0 2.25 2.25t-2.25 2.25");
}

</style>
