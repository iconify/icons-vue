<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r29q2yqsl"/><path class="v0ts39w3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:finhay" /></template>
<style>
.r29q2yqsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.389 14.703c1.002.218 2.036 1.16 2.177 2.177c1.15 8.344-2.982 31.077-21.771 20.32c-1.64-.94-2.985-2.578-3.629-4.355c-4.665-12.88 4.985-22.115 23.223-18.142");
}

.v0ts39w3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.645 8.897c1.003.219 2.037 1.16 2.177 2.177c1.152 8.344-2.981 31.078-21.77 20.32c-1.64-.939-2.986-2.578-3.629-4.354c-4.665-12.881 4.985-22.115 23.222-18.143");
}

</style>
