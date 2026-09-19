<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbip4ib0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asus-data-transfer" /></template>
<style>
.kbip4ib0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.2 11.97V4.5L9.285 9.25v19.202c0 3.808 2.384 6.703 7.91 5.617m2.007-2.535V16.333l19.513-4.88v24.795c-.028 1.7-.857 3.52-2.711 4.044c-3.894 1.1-7.848 1.984-11.774 2.97c-2.75.691-5.028-.118-5.028-2.494v-6.996l12.827-3.696l-5.896-4.305v3.565");
}

</style>
