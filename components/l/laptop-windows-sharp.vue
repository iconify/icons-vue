<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_wo39bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-windows-sharp" /></template>
<style>
.v_wo39bgj {
  fill: currentColor;
  d: path("M1 18.77v-1h3.616V17H3V5h18v12h-1.616v.77H23v1z");
}

</style>
