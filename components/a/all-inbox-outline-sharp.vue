<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afxvf8bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:all-inbox-outline-sharp" /></template>
<style>
.afxvf8bwa {
  fill: currentColor;
  d: path("M8 16h12v-3h-2.55q-.525.925-1.45 1.463T14 15q-1.05 0-1.975-.537T10.55 13H8zm6-3q.85 0 1.425-.587T16 11h4V4H8v7h4q0 .825.588 1.413T14 13m-8 5V2h16v16zm-4 4V6h2v14h14v2zm6-6h12z");
}

</style>
