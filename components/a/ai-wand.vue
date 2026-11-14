<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkm8q1bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-wand" /></template>
<style>
.xkm8q1bmb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.814 4.329v.001l.139.323q.118.276.394.394l.324.139q.701.3.701 1.064t-.702 1.064l-.323.139q-.276.118-.394.394l-.139.324q-.3.701-1.064.701t-1.064-.702l-.139-.323q-.118-.276-.394-.394l-.324-.139q-.701-.3-.701-1.064t.702-1.064l.323-.139q.276-.118.394-.394l.139-.324q.3-.701 1.064-.701q.763 0 1.064.701M12.97 9.97l-9.5 9.5q-.053.052-.094.113t-.069.13t-.043.141T3.25 20t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T4 20.75t.287-.057t.243-.163l9.5-9.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094");
}

</style>
