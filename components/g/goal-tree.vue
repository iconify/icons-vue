<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf8qtnbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goal-tree" /></template>
<style>
.bf8qtnbia {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 1.75h2.5q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-.5v3.5h6.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T20 12v4.011q.876.079 1.518.721q.732.732.732 1.768v1q0 1.036-.732 1.768T19.75 22h-1q-2.5 0-2.5-2.5v-1q0-2.372 2.25-2.493V12.75h-5.75v3.257Q15 16.128 15 18.5v1q0 1.036-.732 1.768T12.5 22h-1Q9 22 9 19.5v-1q0-2.372 2.25-2.493V12.75H5.5v3.257q2.25.121 2.25 2.493v1q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5v-1q0-2.372 2.25-2.493V12q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.5v-3.5h-.5q-2.5 0-2.5-2.5v-1q0-2.5 2.5-2.5");
}

</style>
