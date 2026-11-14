<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf15dlbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-stop-pressed" /></template>
<style>
.jf15dlbgd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.439L10.03 2.47q-.105-.106-.243-.163T9.5 2.25t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T8.75 3t.014.146q.015.073.043.141t.069.13t.094.113l2.5 2.5q.105.106.243.163T12 6.25t.287-.057t.243-.163l2.5-2.5q.053-.052.094-.113t.069-.13t.043-.141T15.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.105-.106-.243-.163T14.5 2.25t-.287.057t-.243.163zm6.69 7.811h2.81q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75v-6q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.81q.306-1.842 2.174-2.984T12 8.125t4.516 1.141q1.868 1.142 2.174 2.984m-11.867 0Q7.37 9.625 12 9.625t5.177 2.625z");
}

</style>
