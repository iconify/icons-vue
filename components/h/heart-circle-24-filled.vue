<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkp6_eupk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-circle-24-filled" /></template>
<style>
.vkp6_eupk {
  fill: currentColor;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10m-.304-5.144L7.59 12.064a2.46 2.46 0 0 1 3.583-3.367L12 9.5l.827-.803a2.461 2.461 0 0 1 3.583 3.367l-4.107 4.792a.4.4 0 0 1-.607 0");
}

</style>
