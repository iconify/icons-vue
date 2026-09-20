<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6e0dbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flight-takeoff-outline" /></template>
<style>
.ax6e0dbaa {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm1.75-5L1 9.75l2.4-.65l2.8 2.35l3.5-.925l-5.175-6.9l2.9-.775L14.9 9.125l4.25-1.15q.8-.225 1.513.187t.937 1.213t-.187 1.513t-1.213.937z");
}

</style>
