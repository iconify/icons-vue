<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqw9ksoyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goal-tile-01" /></template>
<style>
.bqw9ksoyg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.75h8.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501h-8.25q-2.123 0-3.624-1.501T2.75 16.125v-8.25q0-2.123 1.501-3.624T7.875 2.75m-.294 4.831Q5.75 9.411 5.75 12t1.831 4.419T12 18.25t4.419-1.831Q18.25 14.589 18.25 12q0-1.913-1-3.413V7.5l-.001-.036q-.007-.14-.063-.268q-.057-.127-.156-.226q-.105-.106-.243-.163T16.5 6.75h-1.087q-1.5-1-3.413-1q-2.589 0-4.419 1.831");
}

</style>
