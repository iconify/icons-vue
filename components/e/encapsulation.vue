<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4bja4bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:encapsulation" /></template>
<style>
.k4bja4bhx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.324 3.96L3.96 10.324q-1.391 1.391-1.391 3.358T3.96 17.04t3.358 1.391t3.358-1.391l1.074-1.073V14.75q0-.192.036-.38q.037-.188.108-.366q.072-.177.175-.338q.104-.161.237-.3L7.22 8.28q-.106-.105-.163-.243T7 7.75t.057-.287t.163-.243t.243-.163T7.75 7t.287.057t.243.163l5.415 5.415l2.219-.833l1.126-1.126q1.391-1.391 1.391-3.358T17.04 3.96t-3.358-1.391t-3.358 1.391m7.689 8.588l4 1.5q.108.04.198.11t.155.165t.1.203t.034.224v3q0 3.27-4.487 4.952q-.127.048-.263.048t-.263-.048Q13 21.02 13 17.75v-3q0-.115.034-.224t.1-.203t.155-.165t.198-.11l4-1.5q.127-.048.263-.048t.263.048M14.5 15.27v2.48q0 2.145 3.25 3.446Q21 19.895 21 17.75v-2.48l-3.25-1.219z");
}

</style>
