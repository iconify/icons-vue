<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="via631b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:headphones" /></template>
<style>
.via631b-w {
  fill: currentColor;
  d: path("M8.077 20H5.616q-.691 0-1.153-.462T4 18.384V12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4t3.118.626T17.66 6.34t1.714 2.542T20 12v6.385q0 .69-.462 1.152T18.384 20h-2.461v-6.154H19V12q0-2.925-2.037-4.962T12 5T7.038 7.038T5 12v1.846h3.077z");
}

</style>
