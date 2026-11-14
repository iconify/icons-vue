<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev5nam_ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:karaoke" /></template>
<style>
.ev5nam_ze {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 8.5q0-2.175 1.538-3.712Q13.325 3.25 15.5 3.25t3.712 1.538Q20.75 6.325 20.75 8.5t-1.538 3.712Q17.675 13.75 15.5 13.75q-.948 0-1.774-.292q-.172.505-.593.899L7.295 19.83q-1.562 1.464-3.075-.05q-1.514-1.513-.05-3.075l5.473-5.838q.394-.421.899-.593q-.292-.826-.292-1.774m7.28 3.72l-5.75-5.75q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T10.5 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113l5.75 5.75q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243");
}

</style>
