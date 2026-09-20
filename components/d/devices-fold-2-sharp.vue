<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdxia4ont"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-fold-2-sharp" /></template>
<style>
.pdxia4ont {
  fill: currentColor;
  d: path("M5 21V3h13.95l4 10H19v8zm2-2h10v-6H8.05L7 10.375z");
}

</style>
