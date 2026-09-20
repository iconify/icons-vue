<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_rqy8bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:anchor-outline-sharp" /></template>
<style>
.r_rqy8bus {
  fill: currentColor;
  d: path("M8.885 20.614q-1.475-.502-2.583-1.375T4.54 17.177t-.655-2.561v-1.808l2.73 2.058l-1.396 1.396q.725 1.679 2.397 2.69q1.67 1.012 3.884 1.146v-9.021h-3v-1h3V7.825q-.856-.21-1.428-.876T9.5 5.385q0-1.039.73-1.77q.732-.73 1.77-.73t1.77.73q.73.731.73 1.77q0 .898-.572 1.564q-.572.667-1.428.876v2.252h3v1h-3v9.021q2.214-.134 3.894-1.136t2.387-2.681l-1.397-1.416l2.731-2.057v1.807q0 1.373-.655 2.562q-.654 1.188-1.762 2.061t-2.583 1.375t-3.115.503t-3.116-.502M12 6.884q.617 0 1.059-.44q.441-.442.441-1.06q0-.617-.441-1.058q-.442-.441-1.059-.441t-1.059.441t-.441 1.059t.441 1.058T12 6.885");
}

</style>
