<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zrh_rcbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:convertit" /></template>
<style>
.zrh_rcbzb {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5v43m-9.111-33.721V36.22m18.222-24.441V36.22m9.111-15.664v6.888M5.778 20.556v6.888");
}

</style>
