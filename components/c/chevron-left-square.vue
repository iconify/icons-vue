<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amalv35zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-left-square" /></template>
<style>
.amalv35zs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75M9.22 12.53q-.106-.105-.163-.243T9 12t.057-.287t.163-.243l4-4q.105-.106.243-.163t.287-.057t.287.057t.243.163q.053.052.094.113t.069.13t.043.141T14.5 8t-.014.146q-.015.073-.043.141t-.069.13t-.094.113L10.811 12l3.469 3.47q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163z");
}

</style>
