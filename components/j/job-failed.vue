<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwvyvlbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:job-failed" /></template>
<style>
.rwvyvlbuc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.485 0 4.243 1.757Q21.75 5.765 21.75 8.25v7.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 18.235 2.25 15.75v-7.5q0-2.485 1.757-4.243Q5.765 2.25 8.25 2.25M13.061 12l2.969-2.97q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094L12 10.939L9.03 7.97q-.105-.106-.243-.163T8.5 7.75t-.287.057t-.243.163t-.163.243t-.057.287t.057.287t.163.243L10.939 12L7.97 14.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163L12 13.061l2.97 2.969q.105.106.243.163t.287.057t.287-.057t.243-.163q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243z");
}

</style>
