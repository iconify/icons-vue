<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njs0h2fdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cortado" /></template>
<style>
.njs0h2fdn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 4v2.75h10.5V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T18 3.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v13.5q0 3.25-3.25 3.25h-7q-3.25 0-3.25-3.25V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 3.25 6 3.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T6.75 4m0 9.25v4.25q0 1.75 1.75 1.75h7q1.75 0 1.75-1.75v-4.25zm10.5-1.5v-3.5H6.75v3.5z");
}

</style>
