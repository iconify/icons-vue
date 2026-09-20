<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2y-e545n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:card-travel-outline-sharp" /></template>
<style>
.u2y-e545n {
  fill: currentColor;
  d: path("M4 19h16v-2H4zm-2 2V6h5V2h10v4h5v15zm2-7h16V8h-3v2h-2V8H9v2H7V8H4zm5-8h6V4H9zM4 19V8v2v-2v2v-2z");
}

</style>
