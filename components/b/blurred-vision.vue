<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3cw2uihz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blurred-vision" /></template>
<style>
.y3cw2uihz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.75q-6.166 0-10.136 6.353q-.056.089-.085.19t-.029.207q0 .105.029.207t.085.19Q5.834 17.25 12 17.25t10.136-6.353q.056-.089.085-.19t.029-.207q0-.105-.029-.207t-.085-.19Q18.166 3.75 12 3.75M12 7q3.5 0 3.5 3.5T12 14t-3.5-3.5T12 7m0 12q-3.939 0-7.47-3.53q-.052-.053-.113-.094t-.13-.069t-.141-.043T4 15.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113Q7.439 20.5 12 20.5t8.53-3.97q.106-.105.163-.243T20.75 16t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 15.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094Q15.939 19 12 19");
}

</style>
