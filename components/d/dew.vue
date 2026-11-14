<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvv6o3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dew" /></template>
<style>
.rvv6o3bix {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.095 7.095Q2.25 11.939 2.25 19q0-.149.057-.287t.163-.243l9-9q.052-.053.113-.094t.13-.069t.141-.043T12 9.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-9 9q-.105.106-.243.163T3 19.75q7.061 0 11.905-4.845Q19.75 10.061 19.75 3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25q-7.061 0-11.905 4.845m10.602 6.898q.022-.024.046-.046q.055-.05.118-.088t.132-.064q.07-.025.143-.036q.073-.012.147-.008q.073.003.145.02t.139.049t.126.075t.11.098Q21.75 17.208 21.75 19q0 3.5-3.5 3.5t-3.5-3.5q0-1.792 2.947-5.007M16.25 19q0-1.069 2-3.374q2 2.305 2 3.374q0 2-2 2t-2-2");
}

</style>
