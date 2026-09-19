<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9ngnfzqa"/><path class="u7r5yf0ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adw-launcher" /></template>
<style>
.u7r5yf0ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.195 29.119c2.88 6.41 9.321 10.875 16.805 10.875S37.925 35.53 40.805 29.12m-8.646-12.955v-4.563h4.92v9.483");
}

.x9ngnfzqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 27.506L24 8.006l-19.5 19.5m22.775 12.021L24 36.252l-3.275 3.275");
}

</style>
