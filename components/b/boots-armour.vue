<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2m4x7bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boots-armour" /></template>
<style>
.w2m4x7bqh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 5.95V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h9q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.877q1.5.437 1.5 2.373v.5q0 1.936-1.5 2.373v.886l3.526 1.543q2.406.864 2.474 3.428V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 21v-9.877q-1.5-.437-1.5-2.373v-.5q0-1.036.732-1.768q.35-.349.768-.532m1.5-.2h7.5v-2h-7.5zm0 5.5v9h13.5v-3.24q-.045-1.539-1.5-2.053q-.026-.009-.051-.02l-4-1.75q-.1-.044-.183-.114q-.084-.071-.144-.162t-.091-.197t-.031-.214v-1.25z");
}

</style>
