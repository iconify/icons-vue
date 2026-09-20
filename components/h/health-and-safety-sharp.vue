<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmyrb_xmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-and-safety-sharp" /></template>
<style>
.nmyrb_xmr {
  fill: currentColor;
  d: path("M11 15h2v-2.5h2.5v-2H13V8h-2v2.5H8.5v2H11zm1 5.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963");
}

</style>
