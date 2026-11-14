<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7udn1v7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cargo-airdrop" /></template>
<style>
.c7udn1v7f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.457 5.045Q4.25 7.363 4.25 11q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.14l3.769 4.712q-.159.439-.159 1.038v2q0 2.25 2.25 2.25h2q2.25 0 2.25-2.25v-2q0-.599-.159-1.038l3.769-4.712H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.638-2.207-5.955Q15.357 2.75 12 2.75T6.457 5.045M16.94 11.75l-2.922 3.652q-.433-.152-1.018-.152h-2q-.585 0-1.018.152L7.06 11.75z");
}

</style>
