<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imfjcwbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:content-tag" /></template>
<style>
.imfjcwbfc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25Q2.25 2.25 2.25 5v6.5q0 .149.057.287t.163.243l9.5 9.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l8.5-8.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-9.5-9.5q-.105-.106-.243-.163T11.5 2.25zM5.5 8q0-2.5 2.5-2.5T10.5 8T8 10.5T5.5 8");
}

</style>
