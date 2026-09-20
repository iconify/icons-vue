<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4tlkdbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:buttons-alt-outline-sharp" /></template>
<style>
.o4tlkdbta {
  fill: currentColor;
  d: path("M3 17V7h18v10zm1-1h16V8H4zm3.558-1.5h.884v-2.058H10.5v-.884H8.442V9.5h-.884v2.058H5.5v.884h2.058zM4 16V8z");
}

</style>
