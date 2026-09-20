<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr8sux5bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-left-rounded" /></template>
<style>
.xr8sux5bu {
  fill: currentColor;
  d: path("M8.404 21q-.69 0-1.153-.462t-.462-1.153v-7.712H5.615q-.69 0-1.153-.462T4 10.058V6.616q0-.691.463-1.153T5.616 5h5.173q.309 0 .539.23t.23.54v13.615q0 .69-.463 1.153T9.942 21zm10.173-8.913q-1.423 1.586-3.538 1.586q-.31 0-.52-.21t-.211-.52V3.73q0-.31.21-.52t.52-.211q2.116 0 3.539 1.577T20 8.327t-1.423 3.76");
}

</style>
