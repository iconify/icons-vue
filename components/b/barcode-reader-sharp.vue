<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6da-lb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:barcode-reader-sharp" /></template>
<style>
.d6da-lb1h {
  fill: currentColor;
  d: path("M6 19.462q-1 0-1.59-.778q-.589-.778-.349-1.723l1.897-7.126q-.806-.275-1.382-1.05T4 7q0-1.246.877-2.123T7 4h9.61l-3 6h-3.558l-.371 1.404h.858v3H8.88l-.943 3.608q-.179.648-.719 1.049T6 19.46M17.98 4.655l-.393-.87l3.125-1.418l.388.875zm2.732 6.98l-3.125-1.393l.394-.875l3.119 1.419zm-2.596-4.153V6.52h3.461v.962z");
}

</style>
