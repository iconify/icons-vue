<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3rcclb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-off" /></template>
<style>
.c3rcclb0k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m16.665 14.896L8.778 5.949q1.891-1.414 4.29-1.196q2.587.235 4.251 2.231q1.446 1.736 1.457 3.919q1.298.388 2.152 1.526q1.064 1.42.813 3.177q-.189 1.328-1.046 2.26M7 19.25h9.422L6.456 9.285q-.067.248-.115.506q-1.548.198-2.7 1.35Q2.25 12.532 2.25 14.5t1.391 3.359T7 19.25");
}

</style>
