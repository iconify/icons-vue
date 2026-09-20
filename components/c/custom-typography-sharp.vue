<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybx1o7bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:custom-typography-sharp" /></template>
<style>
.ybx1o7bhu {
  fill: currentColor;
  d: path("M11 22v-6h2v2h8v2h-8v2zm-8-2v-2h6v2zm3.425-6H8.5l1.1-3.075h4.825L15.5 14h2.075l-4.5-12h-2.15zM10.2 9.2l1.75-4.975h.1L13.8 9.2z");
}

</style>
