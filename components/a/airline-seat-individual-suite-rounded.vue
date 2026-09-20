<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eibilqbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-individual-suite-rounded" /></template>
<style>
.eibilqbjl {
  fill: currentColor;
  d: path("M3 17q-.825 0-1.412-.587T1 15V8q0-.425.288-.712T2 7t.713.288T3 8v7h8V9q0-.825.588-1.412T13 7h6q1.65 0 2.825 1.175T23 11v4q0 .825-.587 1.413T21 17zm6.125-3.875Q10 12.25 10 11t-.875-2.125T7 8t-2.125.875T4 11t.875 2.125T7 14t2.125-.875");
}

</style>
