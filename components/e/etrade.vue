<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vza3we77n"/><path class="w5hezucjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:etrade" /></template>
<style>
.vza3we77n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.24 3.655l11.745 20.344L17.24 44.344l-7.475-4.318l6.761-11.712H3v-8.63h13.527L9.766 7.968Z");
}

.w5hezucjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.764 3.655l-6.763 11.712L28.984 24l-4.983 8.63l6.763 11.716l7.475-4.318l-6.764-11.712H45v-8.63H31.475L38.24 7.969Z");
}

</style>
