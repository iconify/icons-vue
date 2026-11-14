<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9y1-mb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:antenna-dipole" /></template>
<style>
.k9y1-mb6p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 3.75h-4q-2.5 0-2.5 2.5t2.5 2.5h3.91l3.09 3.532V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-8.218l3.09-3.532h3.91q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732h-4q-2.5 0-2.5 2.5q0 1.525.93 2.12L12 10.861L9.82 8.37q.93-.595.93-2.12q0-2.5-2.5-2.5");
}

</style>
