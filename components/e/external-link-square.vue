<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7h_lkbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:external-link-square" /></template>
<style>
.z7h_lkbhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.75q0 2.848-2.014 4.861t-4.861 2.014h-4.75q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75M15 8.25h-4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.75 9t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.689L8.47 14.47q-.106.105-.163.243T8.25 15t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l4.72-4.719V13.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-.149-.057-.287t-.163-.243q-.105-.106-.243-.163T15 8.25");
}

</style>
