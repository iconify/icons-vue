<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxrcbybul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:image-square" /></template>
<style>
.vxrcbybul {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.75h8.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 .945-.297 1.767L17.03 13.97q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163l-1.47 1.469l-4.97-4.969q-.105-.106-.243-.163T9 10.25t-.287.057t-.243.163l-5.5 5.5q-.088.087-.143.198t-.071.234q-.006-.137-.006-.277v-8.25q0-2.123 1.501-3.624T7.875 2.75M13 8.5q0 2.5 2.5 2.5T18 8.5T15.5 6T13 8.5m6.97 10.53q.113.113.262.17q-.218.284-.483.549q-1.501 1.501-3.624 1.501h-8.25q-2.123 0-3.624-1.501q-1.29-1.291-1.471-3.041q.053.186.19.322q.105.106.243.163t.287.057t.287-.057t.243-.163L9 12.061l4.97 4.969q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l1.47-1.469z");
}

</style>
