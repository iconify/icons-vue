<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9j02ab-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-check" /></template>
<style>
.j9j02ab-v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.201 4.953l-4.5 3.937Q3.25 10.16 3.25 12.088V16.5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5v-4.412q0-1.928-1.451-3.198l-4.5-3.937q-2.799-2.45-5.598 0M11 15.439l3.47-3.469q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-4 4q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2-2q-.106-.105-.163-.243T8.25 14.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 13.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
