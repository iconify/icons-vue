<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klmnkobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-pressure" /></template>
<style>
.klmnkobbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.166 4.666Q3.75 7.083 3.75 10.5t2.416 5.834q1.636 1.635 3.731 2.164q-.147.428-.147 1.002v.5q0 2.25 2.25 2.25T14.25 20v-.5q0-.574-.147-1.002q2.095-.529 3.731-2.164q2.416-2.417 2.416-5.834t-2.416-5.834T12 2.25T6.166 4.666m5.304 5.303l3.5-3.499q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243T16.25 7t-.057.287t-.163.243l-3.422 3.423q-.052.069-.119.124q-.067.056-.145.095q-.078.038-.162.058q-.085.02-.172.02H12q-.149 0-.287-.057t-.243-.163q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243z");
}

</style>
