<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjpxt5b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gesture-select-sharp" /></template>
<style>
.gjpxt5b2k {
  fill: currentColor;
  d: path("M1 12v-2h2v2zm20 0v-2h2v2zM1 8V6h2v2zm20 0V6h2v2zM1 4V2h2v2zm4 8v-2h2v2zm12 0v-2h2v2zm4-8V2h2v2zM5 4V2h2v2zm4 0V2h2v2zm4 0V2h2v2zm4 0V2h2v2zm-5.175 19q-.6 0-1.15-.225t-.975-.65L4.6 17l1.6-1.625l2.8.8V7h2v8h1v-4h2v4h1v-3h2v3h1v-1h2v5q0 1.65-1.175 2.825T16 23z");
}

</style>
