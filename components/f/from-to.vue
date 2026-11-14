<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8t9f90am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:from-to" /></template>
<style>
.v8t9f90am {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.03 6.47l5 5q.106.105.163.243t.057.287t-.057.287t-.163.243l-5 5q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 17t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.719-3.72H8.201Q7.85 15.25 5 15.25q-3.25 0-3.25-3.25T5 8.75q2.85 0 3.201 2.5h10.488L14.97 7.53q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 7t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094");
}

</style>
