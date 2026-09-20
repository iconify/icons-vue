<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbs8b4mxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:frame-spark-sharp" /></template>
<style>
.mbs8b4mxz {
  fill: currentColor;
  d: path("M20 10V6h-4V4h6v6zM2 10V4h6v2H4v4zm14 10v-2h4v-4h2v6zM2 20v-6h2v4h4v2zm10-3.5q.175 0 .2-.15q.4-1.525 1.513-2.637T16.35 12.2q.15-.05.15-.2q0-.175-.15-.2q-1.525-.4-2.637-1.512T12.2 7.65q-.05-.15-.2-.15t-.2.15q-.4 1.525-1.512 2.638T7.65 11.8q-.15.025-.15.2q0 .15.15.2q1.525.4 2.638 1.513T11.8 16.35q.05.15.2.15");
}

</style>
