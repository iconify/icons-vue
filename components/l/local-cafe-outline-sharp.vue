<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqmmrybnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-cafe-outline-sharp" /></template>
<style>
.pqmmrybnr {
  fill: currentColor;
  d: path("M4 21v-2h16v2zm0-4V3h18v7h-4v7zm2-2h10V5H6zm12-7h2V5h-2zM6 15h10z");
}

</style>
