<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op05vuwiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:direct-report" /></template>
<style>
.op05vuwiz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 4.5q0-2.75 2.75-2.75t2.75 2.75q0 2.345-2 2.69v3.56h5.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.054q2.25.348 2.25 2.946q0 3-3 3t-3-3q0-2.598 2.25-2.946V12.25H6.25v1.304q2.25.348 2.25 2.946q0 3-3 3t-3-3q0-2.598 2.25-2.946V11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5.75V7.19q-2-.345-2-2.69");
}

</style>
