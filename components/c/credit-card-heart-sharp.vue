<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgma86npn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-heart-sharp" /></template>
<style>
.hgma86npn {
  fill: currentColor;
  d: path("m17.535 19.885l-2.962-2.962q-.287-.287-.395-.597q-.109-.311-.109-.622q0-.68.483-1.211t1.24-.532q.602 0 .945.277q.344.277.798.731q.442-.442.79-.725t.961-.283q.781 0 1.248.532T21 15.705q0 .319-.121.638t-.383.58zM3 19V5h18v6.287q-.238-.153-.479-.278q-.24-.124-.521-.222v-1.98H4v2.385h10.385q-1.552.797-2.509 2.324q-.957 1.528-.957 3.407q0 .549.089 1.072t.26 1.005z");
}

</style>
