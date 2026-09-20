<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2h46eb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:funicular-outline-sharp" /></template>
<style>
.h2h46eb-f {
  fill: currentColor;
  d: path("M2 22v-1.02l5.25-1.451v-3.145H4V6H3V5h2.885V3.77h12.23V5H21v1h-1v8.577h-3.212v2.356L22 15.5v1.02zm6.712-2.867l6.615-1.804v-2.752H12.5v1.808H8.711zM5 15.385h6.5V14H5zm7.5-1.808H19v-1.385h-6.5zM5 13h6.5V6H5zm7.5-1.808H19V6h-6.5zm-1 4.193V14zm1-1.808v-1.385z");
}

</style>
