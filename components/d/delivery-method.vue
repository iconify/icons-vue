<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofptnac2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-method" /></template>
<style>
.ofptnac2y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8v9q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.108q-.108.353-.108.75q0 1.036.732 1.768q.732.733 1.768.733t1.768-.733q.733-.732.732-1.768q0-.397-.107-.75h4.674q-.067.342-.067.75q0 2.5 2.5 2.5t2.5-2.5q0-.408-.067-.75H20.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-.149-.057-.287t-.163-.243l-3.5-3.5q-.105-.106-.243-.163T17 8.75h-3.25V6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T13 5.25H4.5q-1.139 0-1.945.805Q1.75 6.861 1.75 8m16.081 8.25Q17.291 16 16.5 16t-1.331.25H13.75v-6h2.939l3.061 3.061v2.939z");
}

</style>
