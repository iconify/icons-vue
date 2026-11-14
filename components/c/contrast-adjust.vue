<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i08jmobso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contrast-adjust" /></template>
<style>
.i08jmobso {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.75q0 2.848-2.014 4.861t-4.861 2.014h-4.75q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75M7.581 7.581Q5.75 9.411 5.75 12t1.831 4.419T12 18.25t4.419-1.831Q18.25 14.589 18.25 12t-1.831-4.419Q14.589 5.75 12 5.75T7.581 7.581M12 7.75q1.76 0 3.005 1.245T16.25 12t-1.245 3.005T12 16.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-7q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 7.75");
}

</style>
