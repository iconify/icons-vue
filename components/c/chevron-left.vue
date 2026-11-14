<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw51_yhly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-left" /></template>
<style>
.cw51_yhly {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.47 19.03l-6.5-6.5q-.106-.105-.163-.243T7.75 12t.057-.287t.163-.243l6.5-6.5q.105-.106.243-.163T15 4.75t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113L9.561 12l5.969 5.97q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T15 19.25t-.287-.057t-.243-.163");
}

</style>
