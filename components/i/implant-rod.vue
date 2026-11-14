<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puv5z-b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:implant-rod" /></template>
<style>
.puv5z-b6u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.849 8.336Q12 3.152 2.151 8.336q-.066.035-.123.081q-.057.047-.105.104t-.082.121t-.057.136q-.022.07-.03.144t-.001.147t.028.144t.055.136t.081.123t.104.105t.121.082t.136.057q.07.022.144.03t.147.001t.144-.028t.136-.055q9.151-4.816 18.302 0q.065.034.136.055t.144.028t.147-.001t.144-.03t.136-.057t.121-.082q.057-.048.104-.105t.081-.123t.055-.136t.028-.144t-.001-.147t-.03-.144t-.057-.136t-.082-.121t-.105-.104t-.123-.081M5 12.75h14q2.25 0 2.25 2.25T19 17.25H5q-2.25 0-2.25-2.25T5 12.75");
}

</style>
