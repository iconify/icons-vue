<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m51lrrb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-outline-check" /></template>
<style>
.m51lrrb9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8.75q0 5.49 9.82 12.364q.094.067.205.101q.11.035.225.035t.225-.035q.111-.034.205-.101q9.82-6.874 9.82-12.353q.066-4.614-4.424-5.678q-3.802-.9-5.826 1.939q-2.024-2.839-5.826-1.939Q1.684 4.147 1.75 8.75M11 13.439l3.97-3.969q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.5 4.5q-.105.106-.243.163T11 15.25t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243T7.75 12t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
