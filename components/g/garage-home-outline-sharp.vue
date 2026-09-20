<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pobu7wbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:garage-home-outline-sharp" /></template>
<style>
.pobu7wbzw {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12h-2V10l-6-4.5L6 10v11zm5-2h6v-2H9zm0-4h6v-2H9zm-2 6V11h10v10z");
}

</style>
