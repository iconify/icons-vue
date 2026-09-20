<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e368msbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:accessibility-outline-rounded" /></template>
<style>
.e368msbax {
  fill: currentColor;
  d: path("M10.809 5.268q-.501-.5-.501-1.191q0-.69.5-1.191q.502-.502 1.192-.502t1.191.502q.501.5.501 1.191q0 .69-.5 1.191q-.502.501-1.192.501t-1.191-.5M9.808 21V8.423H4.462q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143H19.54q.212 0 .356.144t.144.357t-.144.356t-.356.143h-5.347V21q0 .213-.144.356q-.143.144-.356.144t-.356-.144t-.144-.356v-5h-2.384v5q0 .214-.144.357t-.357.143t-.356-.144T9.808 21");
}

</style>
