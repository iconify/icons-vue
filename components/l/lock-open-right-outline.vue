<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcdsbrp_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-open-right-outline" /></template>
<style>
.gcdsbrp_g {
  fill: currentColor;
  d: path("M6 20h12V10H6zm7.413-3.588Q14 15.826 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587M6 20V10zm0 2q-.825 0-1.412-.587T4 20V10q0-.825.588-1.412T6 8h7V6q0-2.075 1.463-3.537T18 1t3.538 1.463T23 6h-2q0-1.25-.875-2.125T18 3t-2.125.875T15 6v2h3q.825 0 1.413.588T20 10v10q0 .825-.587 1.413T18 22z");
}

</style>
