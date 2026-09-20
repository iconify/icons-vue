<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hclexsbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-individual-suite-sharp" /></template>
<style>
.hclexsbpt {
  fill: currentColor;
  d: path("M1 17V7h2v8h8V7h12v10zm8.125-3.875Q10 12.25 10 11t-.875-2.125T7 8t-2.125.875T4 11t.875 2.125T7 14t2.125-.875");
}

</style>
