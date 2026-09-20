<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtakkbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-start-sharp" /></template>
<style>
.lbtakkbof {
  fill: currentColor;
  d: path("M3 4V3h18v1zm4.5 5.5v-2h9v2zm0 6v-2h9v2z");
}

</style>
