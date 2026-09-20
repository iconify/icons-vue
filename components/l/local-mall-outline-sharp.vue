<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brrbxackc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-mall-outline-sharp" /></template>
<style>
.brrbxackc {
  fill: currentColor;
  d: path("M3 22V6h4q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6h4v16zm2-2h14V8H5zm10.538-7.462Q17 11.075 17 9h-2q0 1.25-.875 2.125T12 12t-2.125-.875T9 9H7q0 2.075 1.463 3.538T12 14t3.538-1.463M9 6h6q0-1.25-.875-2.125T12 3t-2.125.875T9 6M5 20V8z");
}

</style>
