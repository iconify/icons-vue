<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l620p7b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:helmet-with-visor" /></template>
<style>
.l620p7b9o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.78 10.75q.24-2.937 2.386-5.084Q7.583 3.25 11 3.25t5.834 2.416q2.146 2.147 2.386 5.084h2.28q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V17q0 1.346-.952 2.298T19 20.25h-3.5q-3.25 0-3.25-3.25v-4.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm10.97 1.5V17q0 1.75 1.75 1.75H19q.725 0 1.237-.513q.513-.512.513-1.237v-4.75zm3.963-1.5q-.234-2.317-1.94-4.023Q13.796 4.75 11 4.75T6.227 6.727q-1.706 1.706-1.94 4.023z");
}

</style>
