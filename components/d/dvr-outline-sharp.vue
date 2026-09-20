<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzhupk6cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dvr-outline-sharp" /></template>
<style>
.pzhupk6cy {
  fill: currentColor;
  d: path("M7.434 13.434q.182-.182.182-.434t-.182-.434T7 12.385t-.434.181t-.181.434t.181.434t.434.182t.434-.182m0-4q.182-.182.182-.434t-.182-.434T7 8.385t-.434.181T6.385 9t.181.434t.434.182t.434-.182M9.116 13.5H17.5v-1H9.116zm0-4H17.5v-1H9.116zM9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
