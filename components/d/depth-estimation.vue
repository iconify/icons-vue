<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejkq9ob0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:depth-estimation" /></template>
<style>
.ejkq9ob0b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2.25h18q.149 0 .287.057t.243.163q.093.093.149.212t.068.251q.003.033.003.067v18q0 .149-.057.287t-.163.243q-.105.106-.243.163T21 21.75H3q-.129 0-.251-.043q-.121-.043-.222-.125q-.03-.024-.057-.052q-.106-.105-.163-.243T2.25 21V3q0-.149.057-.287t.163-.243t.243-.163T3 2.25m1.811 1.5l4.5 4.5h5.378l4.5-4.5zM3.75 19.189l4.5-4.5V9.311l-4.5-4.5zm12-4.5l4.5 4.5V4.811l-4.5 4.5zm-6-.439h4.5v-4.5h-4.5zm4.939 1.5H9.311l-4.5 4.5h14.378z");
}

</style>
