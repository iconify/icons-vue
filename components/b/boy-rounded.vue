<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxi4rpbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:boy-rounded" /></template>
<style>
.zxi4rpbni {
  fill: currentColor;
  d: path("M11.032 7.099q-.397-.401-.397-.968t.4-.965t.969-.397t.964.401q.398.401.398.968t-.401.965t-.969.397t-.964-.401m-.378 11.055v-3.808h-.192q-.344 0-.576-.232t-.232-.575V9.923q0-.555.395-.95q.396-.396.951-.396h2q.555 0 .95.395q.396.396.396.951v3.616q0 .343-.232.575t-.576.232h-.192v3.808q0 .343-.232.575t-.576.233h-1.077q-.343 0-.575-.233t-.232-.575");
}

</style>
