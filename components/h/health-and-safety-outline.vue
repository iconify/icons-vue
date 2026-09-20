<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqsg5tbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-and-safety-outline" /></template>
<style>
.jqsg5tbem {
  fill: currentColor;
  d: path("M11 15h2v-2.5h2.5v-2H13V8h-2v2.5H8.5v2H11zm1 5.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m0-1.062q2.6-.825 4.3-3.3t1.7-5.5V6.375l-6-2.23l-6 2.23V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.88");
}

</style>
