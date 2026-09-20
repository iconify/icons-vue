<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uprl03ese"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:antar" /></template>
<style>
.uprl03ese {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.011 43.5l-6.037-2.959h-12.15c-6.293-.07-12.368-3.443-15.612-9.355c-4.786-8.725-1.593-19.678 7.132-24.465a18 18 0 0 1 8.65-2.221c9.962.01 18.027 8.094 18.018 18.056zm-6.037-9.025V17.794");
}

</style>
