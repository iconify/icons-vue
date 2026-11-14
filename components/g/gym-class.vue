<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkndkxm-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gym-class" /></template>
<style>
.kkndkxm-y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.091 6.909Q6.432 6.25 5.5 6.25q-2.25 0-2.25 2.25v2.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.75v2.75q0 2.25 2.25 2.25q.932 0 1.591-.659T7.75 15.5v-2.75h8.5v2.75q0 2.25 2.25 2.25t2.25-2.25v-2.75h.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.75V8.5q0-2.25-2.25-2.25T16.25 8.5v2.75h-8.5V8.5q0-.932-.659-1.591");
}

</style>
