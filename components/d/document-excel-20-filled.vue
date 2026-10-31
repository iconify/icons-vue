<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fvt4ujbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-excel-20-filled" /></template>
<style>
.fvt4ujbbt {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2zm2-2.5A1.5 1.5 0 0 0 11.5 8H16v8.5a1.5 1.5 0 0 1-1.5 1.5h-4.269A2.98 2.98 0 0 0 11 16v-5a3 3 0 0 0-3-3H4V3.5A1.5 1.5 0 0 1 5.5 2H10zm-5.275 6.996L3.195 16H4.47l.88-1.58c.05-.101.083-.153.125-.265h.014c.032.087.054.138.115.251L6.452 16h1.352l-1.488-2.542L7.762 11h-1.27l-.783 1.408c-.069.129-.094.181-.16.318h-.015c-.047-.118-.087-.188-.146-.303L4.634 11H3.3zM15.75 7H11.5a.5.5 0 0 1-.5-.5V2.25z");
}

</style>
