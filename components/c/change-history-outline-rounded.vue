<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz70jnn1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:change-history-outline-rounded" /></template>
<style>
.wz70jnn1e {
  fill: currentColor;
  d: path("M3.8 20q-.575 0-.875-.513t.025-1.012l8.2-13.125q.3-.475.85-.475t.85.475l8.2 13.125q.325.5.025 1.013T20.2 20zm1.8-2h12.8L12 7.75zm6.4-5.125");
}

</style>
