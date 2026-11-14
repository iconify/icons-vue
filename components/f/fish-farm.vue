<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2tc1wb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-farm" /></template>
<style>
.p2tc1wb1q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q1.76 0 3.005 1.245T21.25 7v10q0 1.76-1.245 3.005T17 21.25H7q-1.76 0-3.005-1.245T2.75 17V7q0-1.76 1.245-3.005T7 2.75m4.031 5.688q-3.307 0-5.405 3.146q-.062.092-.094.199q-.032.106-.032.217t.032.217t.094.199q2.098 3.147 5.405 3.147q2.893 0 4.42-2.373l1.797 1.617q.104.093.233.143q.13.05.269.05q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.5q0-.139-.05-.269q-.05-.129-.143-.233q-.099-.111-.234-.175t-.284-.072t-.289.042t-.252.15l-1.797 1.617q-1.527-2.372-4.42-2.372");
}

</style>
