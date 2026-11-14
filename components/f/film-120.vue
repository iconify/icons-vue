<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzh6ctmfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:film-120" /></template>
<style>
.jzh6ctmfl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 1.75h10.5q2 0 2 2t-2 2h-.076q.076.337.076.75v.75H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.75v.75q0 .413-.076.75h.076q2 0 2 2t-2 2H6.75q-2 0-2-2t2-2h.076q-.076-.337-.076-.75v-11q0-.413.076-.75H6.75q-2 0-2-2t2-2m13.5 7h-3v6.5h3z");
}

</style>
