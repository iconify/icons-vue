<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcc5o9bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-pond" /></template>
<style>
.mcc5o9bqb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m9-3.187q-3.705 0-5.617 2.76q-.065.094-.099.203T5 12t.034.224t.099.203q1.912 2.761 5.617 2.761q3.227 0 5.094-2.095l1.904 1.714q.104.093.233.143q.13.05.269.05q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.5q0-.139-.05-.269q-.05-.129-.143-.233q-.099-.111-.234-.175t-.284-.072t-.289.042t-.252.15l-1.904 1.714q-1.867-2.094-5.094-2.094");
}

</style>
