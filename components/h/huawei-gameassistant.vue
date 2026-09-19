<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ezvc76bnj"/><path class="zm59urmer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-gameassistant" /></template>
<style>
.ezvc76bnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.147 41.575l.132-13.215l3.958.037c-.115 5.796 6.798 4.982 6.787.073l3.372.031l-.047 4.682c4.232-1.498 4.951 5.347-.038 3.876l-.047 4.658Z");
}

.zm59urmer {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.906 42.5l-13.216-.243l-.003-3.706c5.796.052 4.904-6.852-.005-6.787l-.003-3.373l4.682-.004c-1.543-4.215 5.294-5.007 3.877-.003l4.657-.003Zm4.947-29.606l-6.921 11.259l-3.41-2.193c3.085-4.908-3.188-7.529-5.707-3.315l-2.91-1.886l2.452-3.988c-4.399-.897-1.489-7.134 2.03-3.303l2.44-3.968ZM7.005 10.135h13.217v3.958c-5.797-.057-4.91 6.848 0 6.787v3.373H15.54c1.54 4.217-5.297 5.004-3.877 0H7.006Z");
}

</style>
