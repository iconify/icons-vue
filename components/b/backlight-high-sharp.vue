<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv1trl4md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backlight-high-sharp" /></template>
<style>
.tv1trl4md {
  fill: currentColor;
  d: path("M1.616 14.5v-1H5v1zm5.08-5.096l-2.421-2.44l.689-.695l2.42 2.447zM7.5 17v-2h9v2zm4-10V2.616h1V7zm5.766 2.385l-.689-.708l2.44-2.402l.695.708zM19 14.5v-1h3.385v1z");
}

</style>
