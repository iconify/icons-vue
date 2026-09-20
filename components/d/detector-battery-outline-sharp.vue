<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcnllgyyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:detector-battery-outline-sharp" /></template>
<style>
.wcnllgyyp {
  fill: currentColor;
  d: path("M9 19h8v-3H9zm-4 2v-7h14v2h2v3h-2v2zM5 5v1h14V5zm3.1 3l.3 1h7.2l.3-1zm-1.15 3L6 8H3V3h18v5h-3l-1.15 3zM5 5v1z");
}

</style>
