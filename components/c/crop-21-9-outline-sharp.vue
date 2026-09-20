<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koymt7bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-21-9-outline-sharp" /></template>
<style>
.koymt7bfv {
  fill: currentColor;
  d: path("M3 16V8h18v8zm1-1h16V9H4zm0 0V9z");
}

</style>
