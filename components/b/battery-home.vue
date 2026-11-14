<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyh4i6bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-home" /></template>
<style>
.fyh4i6bxd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v6.164q0 3.375-3.375 3.375H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m9.44 2.107h-4.75q-3.375 0-3.375 3.375v.25q0 3.375 3.375 3.375h4.75q2.25 0 3-1.5H17.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.125q-.75-1.5-3-1.5m3.364 3q.011.182.011.375v-.375zm.011.625q0 .193-.011.375h.011z");
}

</style>
