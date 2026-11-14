<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz5rx7ais"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:color-picker" /></template>
<style>
.nz5rx7ais {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.601 8.287q1.944-1.944 0-3.888t-3.888 0l-.707.707q-.772.772-.931 1.544l-.838-.837q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l.937.938q-.291.185-.583.477l-3.242 3.241q-.441.441-.593 1.047l-.252 1.011q-.221.892.428 1.541t1.541.428l1.012-.252q.605-.152 1.045-.593l3.242-3.242q.292-.292.477-.583l.938.937q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243l-.837-.838q.772-.159 1.544-.931zM2 19q0-3 3-3t3 3t-3 3t-3-3");
}

</style>
