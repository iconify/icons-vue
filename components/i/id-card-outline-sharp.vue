<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfajsabcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:id-card-outline-sharp" /></template>
<style>
.qfajsabcw {
  fill: currentColor;
  d: path("M14.154 12.462h4.077v-1h-4.077zm0-2.77h4.077v-1h-4.077zm-8.385 5.616h6.616v-.166q0-.875-.88-1.355t-2.428-.48t-2.429.48t-.879 1.355zm4.374-4.05q.434-.433.434-1.066t-.434-1.066t-1.066-.434t-1.066.434t-.434 1.066t.434 1.067t1.066.433t1.066-.433M3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
