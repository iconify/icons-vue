<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v03537bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:key-outline-rounded" /></template>
<style>
.v03537bmt {
  fill: currentColor;
  d: path("M6.126 12.874q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357M7 17q-2.077 0-3.538-1.461T2 12t1.462-3.538T7 7q1.54 0 2.778.835q1.238.834 1.807 2.165h8.875q.161 0 .3.056q.14.056.27.186l1.193 1.192q.13.132.184.268q.052.137.052.298t-.052.298t-.184.268l-2.117 2.097q-.106.106-.243.172q-.136.065-.272.07q-.137.007-.274-.034q-.136-.04-.267-.127l-1.165-.879l-1.368.998q-.105.081-.217.112t-.242.03t-.245-.04t-.22-.102L14.297 14h-2.713q-.57 1.312-1.807 2.156T7 17m0-1q1.477 0 2.52-.889T10.856 13h3.76l1.43.967q-.019 0-.01.003q.01.003.01-.003l1.858-1.333l1.621 1.222v-.01v.01L21.381 12h-.003h.003l-1-1v-.003V11h-9.525q-.292-1.223-1.336-2.111T7 8Q5.35 8 4.175 9.175T3 12t1.175 2.825T7 16");
}

</style>
