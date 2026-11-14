<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnae1yb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-up-square" /></template>
<style>
.rnae1yb-c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75M11.47 9.22q.105-.106.243-.163T12 9t.287.057t.243.163l4 4q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043T16 14.5t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094L12 10.811L8.53 14.28q-.052.053-.113.094t-.13.069t-.141.043T8 14.5t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243z");
}

</style>
