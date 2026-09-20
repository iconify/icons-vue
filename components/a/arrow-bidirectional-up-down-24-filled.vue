<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wex59nkof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-up-down-24-filled" /></template>
<style>
.wex59nkof {
  fill: currentColor;
  d: path("M7.975 9.689a1 1 0 1 1-1.45-1.378l4.75-5a1 1 0 0 1 1.45 0l4.75 5a1 1 0 1 1-1.45 1.378L13 6.505v10.99l3.025-3.184a1 1 0 1 1 1.45 1.378l-4.75 5a1 1 0 0 1-1.45 0l-4.75-5a1 1 0 1 1 1.45-1.378L11 17.496V6.505z");
}

</style>
