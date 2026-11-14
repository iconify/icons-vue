<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndo5m4lre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-nose" /></template>
<style>
.ndo5m4lre {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 7q0-4.25 6.75-4.25T18.75 7q0 2.484-2.368 4.229q-1.727 1.273-3.632 1.48V15.5q0 2.75 3 2.75q3.071 0 3.504-4.325q.015-.148.085-.28q.071-.131.186-.225q.116-.095.258-.138t.292-.028q.073.007.144.029q.07.021.136.056q.065.035.122.082t.103.104t.082.122t.056.136t.028.145q.008.073 0 .147q-.567 5.675-4.996 5.675q-2.663 0-3.75-1.488q-1.087 1.488-3.75 1.488q-4.429 0-4.996-5.675q-.008-.074 0-.147q.007-.074.028-.145t.056-.136t.082-.122t.103-.104t.122-.082t.136-.056t.144-.029t.147 0t.145.028q.07.021.136.056q.065.035.122.082q.057.046.104.103t.082.122q.035.066.056.136q.022.071.029.144q.433 4.325 3.504 4.325q3 0 3-2.75v-2.791q-1.905-.207-3.632-1.48Q5.25 9.484 5.25 7");
}

</style>
