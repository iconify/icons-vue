<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yde364f1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-outline-sharp" /></template>
<style>
.yde364f1h {
  fill: currentColor;
  d: path("M3 19V5h18v14zm9-6.884L4 6.885V18h16V6.885zM12 11l7.692-5H4.308zM4 6.885V6v12z");
}

</style>
