<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5msf3b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:check" /></template>
<style>
.o5msf3b9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.53 11.97l4.97 4.969L19.97 6.47q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T21.25 7t-.057.287t-.163.243l-11 11q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-5.5-5.5q-.106-.105-.163-.243T3.25 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T4 11.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094");
}

</style>
