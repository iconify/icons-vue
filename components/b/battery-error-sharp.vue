<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqvm5vdzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-error-sharp" /></template>
<style>
.eqvm5vdzo {
  fill: currentColor;
  d: path("M16.4 22L15 20.6l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.4 1.4l-2.075 2.1L22 20.6L20.6 22l-2.1-2.075zM7 22V4h3V2h4v2h3v8.7q-1.975.525-3.225 2.138t-1.25 3.687q0 .95.275 1.825t.825 1.65z");
}

</style>
