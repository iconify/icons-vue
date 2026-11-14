<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvjkcub2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-right-circle" /></template>
<style>
.jvjkcub2v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M14.78 11.47q.106.105.163.243T15 12t-.057.287t-.163.243l-4 4q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.5 16t.014-.146q.015-.073.043-.141t.069-.13t.094-.113L13.189 12L9.72 8.53q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.5 8t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163z");
}

</style>
