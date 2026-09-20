<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtrz3vb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-library-outline-rounded" /></template>
<style>
.mtrz3vb0z {
  fill: currentColor;
  d: path("M3 17.15V10q0-.8.588-1.35t1.387-.5q1.975.3 3.763 1.163T12 11.55q1.475-1.375 3.263-2.238t3.762-1.162q.8-.05 1.388.5T21 10v7.15q0 .8-.525 1.363t-1.325.612q-1.6.25-3.1.825t-2.8 1.525q-.275.225-.587.337t-.663.113t-.663-.112t-.587-.338q-1.3-.95-2.8-1.525t-3.1-.825q-.8-.05-1.325-.612T3 17.15m9 2.75q1.575-1.175 3.35-1.875T19 17.1v-6.9q-1.825.325-3.588 1.313T12 14.15q-1.65-1.65-3.412-2.637T5 10.2v6.9q1.875.225 3.65.925T12 19.9M9.175 7.825Q8 6.65 8 5t1.175-2.825T12 1t2.825 1.175T16 5t-1.175 2.825T12 9T9.175 7.825m4.238-1.412Q14 5.825 14 5t-.587-1.412T12 3t-1.412.588T10 5t.588 1.413T12 7t1.413-.587M12 14.15");
}

</style>
