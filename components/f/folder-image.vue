<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-giwsb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-image" /></template>
<style>
.u-giwsb2i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v8q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm12 1.75q-2 0-2 2t2 2q.828 0 1.414-.586t.586-1.414t-.586-1.414t-1.414-.586m-4.319 3.512l-3 3.5q-.049.056-.085.12q-.036.065-.059.135t-.032.144t-.003.147t.026.144t.053.137t.079.124t.102.106q.113.098.255.144t.291.035t.281-.079t.23-.181l2.473-2.885l1.428 1.427q.105.106.243.163t.287.057t.287-.057t.243-.163l.72-.719l2.22 2.219q.105.106.243.163T16.5 17t.287-.057t.243-.163q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243l-2.75-2.75q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163l-.72.719l-1.47-1.469q-.02-.021-.042-.039q-.056-.049-.12-.085q-.065-.036-.135-.059t-.144-.032q-.073-.008-.147-.003q-.073.006-.144.026t-.137.053t-.124.079t-.106.102");
}

</style>
