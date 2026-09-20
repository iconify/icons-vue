<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oytonwbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-4-bar-outline-rounded" /></template>
<style>
.oytonwbsp {
  fill: currentColor;
  d: path("M2.866 18.154v-4.885q0-.352.247-.6q.247-.246.6-.246t.6.247t.245.6v4.884q0 .352-.248.6t-.6.246t-.6-.247q-.244-.246-.244-.6m5.519 0v-7.191q0-.353.247-.6t.601-.246t.599.246t.245.6v7.192q0 .353-.247.6T9.229 19t-.6-.247t-.244-.6m5.519 0V8.636q0-.353.247-.6t.601-.246t.599.246t.245.6v9.519q0 .353-.247.6t-.601.246t-.599-.247t-.245-.6m5.519 0V5.847q0-.352.248-.6t.6-.246t.6.247t.244.6v12.307q0 .353-.247.6t-.601.246t-.599-.247t-.245-.6");
}

</style>
