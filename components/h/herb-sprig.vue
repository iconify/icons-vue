<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvt40bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:herb-sprig" /></template>
<style>
.blvt40bml {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 6.188q0 1.882-1.5 3.171v2.514q2.865-2.915 6.897-2.108q.073.014.141.042t.129.07t.114.093q.052.053.093.114t.069.13q.028.068.043.14t.014.147q0 .074-.015.146q-.469 2.346-2.824 3.58q-2.084 1.091-4.661.69V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 21v-6.083q-2.577.401-4.661-.69q-2.355-1.234-2.824-3.58q-.015-.072-.015-.146t.014-.147q.015-.072.043-.14t.069-.13t.093-.114t.114-.093t.129-.07q.068-.028.141-.042q4.032-.807 6.897 2.108V9.359q-1.5-1.289-1.5-3.171q0-1.999 1.72-3.718q.105-.106.243-.163T12 2.25t.287.057t.243.163q1.72 1.719 1.72 3.718");
}

</style>
