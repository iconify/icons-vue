<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkblfbban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:e911-emergency" /></template>
<style>
.fkblfbban {
  fill: currentColor;
  d: path("M5.692 19v-1h1.466l1.878-6.344q.143-.535.575-.846t.966-.31h2.846q.535 0 .966.31q.432.311.575.846L16.842 18h1.466v1zM11.5 7.885v-4h1v4zm5.45 2.263l-.713-.713l2.838-2.814l.689.689zm1.55 4.737v-1h4v1zM7.05 10.147L4.237 7.31l.688-.689l2.839 2.814zM1.5 14.885v-1h4v1z");
}

</style>
