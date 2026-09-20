<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1syx-k_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-left" /></template>
<style>
.d1syx-k_b {
  fill: currentColor;
  d: path("M8.404 21q-.69 0-1.153-.462t-.462-1.153v-7.712H5.615q-.69 0-1.153-.462T4 10.058V6.616q0-.691.463-1.153T5.616 5h5.942v14.385q0 .69-.463 1.153T9.942 21zm5.904-7.327V3h.73q2.116 0 3.539 1.577T20 8.327t-1.423 3.76t-3.539 1.586z");
}

</style>
