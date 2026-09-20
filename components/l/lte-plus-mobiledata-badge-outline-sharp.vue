<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr03lk-1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-plus-mobiledata-badge-outline-sharp" /></template>
<style>
.lr03lk-1k {
  fill: currentColor;
  d: path("M3 19V5zM22 7.73h-1V5H3v14h18v-2.73h1V20H2V4h20zM5.154 15.5h3.192v-1H6.154v-6h-1zm4.885 0h1v-6h1.692v-1H8.346v1h1.693zm3.807 0h3.385v-1h-2.385v-2h1.885v-1h-1.885v-2h2.385v-1h-3.385zm5.827-1.616h.885v-1.442H22v-.884h-1.442v-1.442h-.885v1.442h-1.442v.884h1.442z");
}

</style>
