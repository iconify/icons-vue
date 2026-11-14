<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_gmpxb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-buildings-cover" /></template>
<style>
.g_gmpxb3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.074 7.616l5.875-4.493q2.051-1.569 4.102 0l5.875 4.493q1.324 1.014 1.324 2.681v8.578q0 3.375-3.375 3.375H13.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.25q0-1.036-.732-1.768T12 15.75q-2.5 0-2.5 2.5v3.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6.125q-3.375 0-3.375-3.375v-8.578q0-1.667 1.324-2.681M10.25 22.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T11 21.5v-3.25q0-1 1-1q.414 0 .707.293t.293.707v3.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm2.25-13h-1q-2.25 0-2.25 2.25v.5q0 2.25 2.25 2.25h1q.932 0 1.591-.659T14.75 12v-.5q0-.932-.659-1.591T12.5 9.25");
}

</style>
