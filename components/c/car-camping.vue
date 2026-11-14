<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgddwu45z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-camping" /></template>
<style>
.zgddwu45z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.223 7.75h5.054L9.75 4.275zm6.919.014q.195.037.346.167l3.289 2.819H20q2.25 0 2.25 2.25v3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.938q.188.531.188 1.25q0 2.75-2.75 2.75t-2.75-2.75q0-.719.188-1.25H9.062q.188.531.188 1.25q0 2.75-2.75 2.75T3.75 18.5q0-.719.188-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V11q0-.167.071-.318t.199-.258l3-2.5q.148-.124.338-.16l3.785-5.205q.044-.06.098-.11t.117-.089t.133-.064t.142-.037t.147-.008t.145.02q.072.017.139.048t.127.074q.096.07.166.166z");
}

</style>
