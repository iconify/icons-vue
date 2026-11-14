<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy20cu__g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-diamond" /></template>
<style>
.sy20cu__g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m22.03 11.47l-9.5-9.5q-.105-.106-.243-.163T12 1.75t-.287.057t-.243.163l-9.5 9.5q-.106.105-.163.243T1.75 12t.057.287t.163.243l9.5 9.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l9.5-9.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113m-9.5-5.25Q16 9.689 16 13.75q0 1.657-1.172 2.828Q13.657 17.75 12 17.75q-4 0-4-4q0-2.561 1.97-4.53q.105-.106.243-.163T10.5 9q.19 0 .357.091q.064-1.293.422-2.547q.041-.143.134-.26q.092-.117.223-.19q.13-.072.278-.089t.292.024q.187.053.324.191");
}

</style>
