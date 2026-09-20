<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caktzqbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-3-2-outline-rounded" /></template>
<style>
.caktzqbdr {
  fill: currentColor;
  d: path("M5.616 17q-.691 0-1.153-.462T4 15.385v-6.77q0-.69.463-1.152T5.616 7h12.769q.69 0 1.153.463T20 8.616v6.769q0 .69-.462 1.153T18.384 17zm0-1h12.769q.23 0 .423-.192t.192-.423v-6.77q0-.23-.192-.423T18.384 8H5.616q-.231 0-.424.192T5 8.616v6.769q0 .23.192.423t.423.192M5 16V8z");
}

</style>
