<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfc_4wb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-windows-outline-sharp" /></template>
<style>
.kfc_4wb1t {
  fill: currentColor;
  d: path("M1 18.77v-1h3.616V17H3V5h18v12h-1.616v.77H23v1zM4 16h16V6H4zm0 0V6z");
}

</style>
