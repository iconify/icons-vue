<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_3_v-w5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fatigue" /></template>
<style>
.m_3_v-w5z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m-1.032 7.923Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h9.396q-1.146-.927-1.146-3v-1q0-2.662 1.89-3.434q-1.627-.566-3.64-.566q-3.462 0-5.782 1.673M16 14.75h3.25q1.036 0 1.768.732q.359.36.542.792q.094-.024.19-.024q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.096 0-.19-.024q-.183.432-.542.792q-.732.732-1.768.732H16q-2.5 0-2.5-2.5v-1q0-2.5 2.5-2.5m.5 1.5H16q-1 0-1 1v1q0 1 1 1h3.25q.414 0 .707-.293t.293-.707v-1q0-1-1-1zm0 0q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5");
}

</style>
