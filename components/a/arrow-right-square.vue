<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1eywmbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-right-square" /></template>
<style>
.o1eywmbog {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.25 14.375q0 2.848-2.014 4.861t-4.861 2.014h-4.75q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861zm-4.22-2.905l-4-4q-.105-.106-.243-.163T12.5 7.25t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T11.75 8t.014.146q.015.073.043.141t.069.13t.094.113l2.719 2.72H7.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.75 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7.189l-2.719 2.72q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l4-4q.106-.105.163-.243T17.25 12t-.057-.287t-.163-.243");
}

</style>
