<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1t7h65-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-center-outline-sharp" /></template>
<style>
.c1t7h65-t {
  fill: currentColor;
  d: path("M3 12.5v-1h18v1zm4.5-3v-2h9v2zm0 7v-2h9v2z");
}

</style>
