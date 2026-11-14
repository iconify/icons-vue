<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1dvcecda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-helmet-cage" /></template>
<style>
.m1dvcecda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 12v7q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H17q4.595 0 4.745-4.913q.005-.043.005-.087q0-.026-.002-.051q.002-.099.002-.199v-4q0-.064-.011-.126q-.01-.063-.032-.123t-.052-.116t-.071-.105q-.04-.05-.087-.092q-.048-.042-.102-.076t-.113-.057t-.122-.038Q20.02 2.25 12.5 2.25q-4.142 0-6.895 2.647Q2.75 7.642 2.75 12m17.5 2h-2.5v-2.75h2.5zm-4 0h-2.5v-2.75h2.5zm-2.5 1.5h2.5v2.75h-2.5zm4 0h2.433q-.342 2.355-2.433 2.693z");
}

</style>
