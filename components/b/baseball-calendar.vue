<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e60xjey8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baseball-calendar" /></template>
<style>
.e60xjey8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 2.5v.75h6.5V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.75h.75q1.76 0 3.005 1.245T21.75 7.5v10q0 1.76-1.245 3.005T17.5 21.75h-11q-1.76 0-3.005-1.245T2.25 17.5v-10q0-1.76 1.245-3.005T6.5 3.25h.75V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q7.926 1.75 8 1.75t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-2 11.5q0 2.175 1.538 3.712Q9.825 19.25 12 19.25t3.712-1.538Q17.25 16.175 17.25 14t-1.538-3.712Q14.175 8.75 12 8.75t-3.712 1.538Q6.75 11.825 6.75 14");
}

</style>
