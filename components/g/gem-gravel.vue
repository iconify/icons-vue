<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwfeudbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gem-gravel" /></template>
<style>
.mwfeudbtm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.75h8q.162 0 .31.067t.254.189l3.5 4q-.107-.122-.254-.189t-.31-.067h-15q-.162 0-.31.067t-.254.189l3.5-4q.106-.122.254-.189T8 2.75M3.89 7.936l6.777 9.489q-.718.217-1.168.703q-.811-.877-2.499-.877q-3.249 0-3.25 3.249q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.25-3.25-3.25q-1.689 0-2.5.878q-.449-.486-1.167-.703l6.777-9.489q-.052.073-.119.131q-.068.059-.148.1t-.166.062t-.177.021h-15q-.09 0-.177-.021t-.166-.062t-.148-.1q-.067-.058-.119-.131");
}

</style>
