<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqrpu-1sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:library-books-sharp" /></template>
<style>
.dqrpu-1sm {
  fill: currentColor;
  d: path("M10 13.5h3.48v-1H10zm0-3h6.962v-1H10zm0-3h6.962v-1H10zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
