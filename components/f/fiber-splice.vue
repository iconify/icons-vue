<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfzm7_b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fiber-splice" /></template>
<style>
.jfzm7_b6s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.375 6.25h-2.75q-3.182 0-3.364 3H4.5q-2.75 0-2.75 2.75t2.75 2.75h2.761q.182 3 3.364 3h2.75q3.182 0 3.364-3H19.5q2.75 0 2.75-2.75T19.5 9.25h-2.761q-.182-3-3.364-3m-1.375 9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-4.75-4.5v2.5H4.5q-1.25 0-1.25-1.25t1.25-1.25zm9.5 0h2.75q1.25 0 1.25 1.25t-1.25 1.25h-2.75z");
}

</style>
