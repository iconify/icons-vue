<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8gcxkips"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:espresso-cup" /></template>
<style>
.w8gcxkips {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 4.75h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.25h.25q3.25 0 3.25 3.25t-3.25 3.25h-.483q-.42 1.492-1.598 2.669q-.173.174-.353.331H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .208-.107.386Q19.925 20.25 17 20.25H7q-2.925 0-4.643-2.864q-.038-.063-.063-.133t-.036-.143t-.007-.146q.003-.074.021-.146t.05-.138t.075-.126t.099-.109t.118-.088q.178-.107.386-.107h2.934q-.18-.157-.353-.331Q3.75 14.089 3.75 11.5v-6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m12.746 7h.254q1.75 0 1.75-1.75T17.5 8.25h-.25v3.25q0 .126-.004.25");
}

</style>
