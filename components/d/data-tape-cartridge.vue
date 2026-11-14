<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtrvizbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-tape-cartridge" /></template>
<style>
.dtrvizbwr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.25H6q-1.76 0-3.005 1.245T1.75 8.5v7q0 1.76 1.245 3.005T6 19.75h12q1.76 0 3.005-1.245T22.25 15.5v-7q0-1.76-1.245-3.005T18 4.25M4.75 11q0-3.25 3.25-3.25q1.346 0 2.298.952T11.25 11q0 .979-.504 1.75h2.338q-.334-.708-.334-1.75q0-3.25 3.25-3.25T19.25 11T16 14.25H7.998Q4.75 14.249 4.75 11");
}

</style>
