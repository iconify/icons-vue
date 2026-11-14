<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is08vp5dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cancel" /></template>
<style>
.is08vp5dp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001-4.039 2.855-6.896T12 2.247t6.895 2.857T21.75 12q.001 4.039-2.855 6.896T12 21.753q-4.04 0-6.895-2.857Q2.249 16.039 2.25 12m10.811 0l3.719-3.72q.106-.105.163-.243T17 7.75t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T16.25 7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094L12 10.939L8.28 7.22q-.105-.106-.243-.163T7.75 7t-.287.057t-.243.163t-.163.243T7 7.75t.057.287t.163.243L10.939 12L7.22 15.72q-.053.052-.094.113t-.069.13t-.043.141T7 16.25t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T7.75 17t.287-.057t.243-.163L12 13.061l3.72 3.719q.105.106.243.163t.287.057t.287-.057t.243-.163q.106-.105.163-.243T17 16.25t-.057-.287t-.163-.243z");
}

</style>
