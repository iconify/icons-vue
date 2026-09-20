<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9_j29f8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fiber-pin-outline-sharp" /></template>
<style>
.v9_j29f8f {
  fill: currentColor;
  d: path("M5.385 14.692h.884v-2.076h3.5V9.308H5.385zm5.98 0h.885V9.308h-.885zm2.866 0h.827V10.77l2.704 3.923h.854V9.308h-.827v3.923l-2.655-3.923h-.903zm-7.962-2.961v-1.539h2.616v1.539zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
