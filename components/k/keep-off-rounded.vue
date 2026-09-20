<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v34008uqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep-off-rounded" /></template>
<style>
.v34008uqc {
  fill: currentColor;
  d: path("M14.07 11.244L7.884 5.06q-.106-.106-.14-.198q-.033-.093-.033-.224q0-.248.157-.443T8.325 4H15.5q.214 0 .357.143T16 4.5q0 .208-.16.322q-.161.115-.34.178H15v5.866q0 .367-.334.504q-.333.138-.597-.126M11.5 20v-5H8.958q-.471 0-.76-.332t-.288-.727q0-.199.074-.387t.247-.362L9 12.423v-1.996L3.216 4.631q-.141-.14-.153-.342t.153-.366q.159-.16.353-.16t.354.16l15.379 15.379q.146.146.153.347t-.159.367q-.165.159-.354.162t-.353-.162L13.573 15H12.5v5q0 .214-.143.357T12 20.5t-.357-.143T11.5 20");
}

</style>
