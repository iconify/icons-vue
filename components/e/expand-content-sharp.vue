<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p85svyawr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-content-sharp" /></template>
<style>
.p85svyawr {
  fill: currentColor;
  d: path("M5 19v-6h2v4h4v2zm12-8V7h-4V5h6v6z");
}

</style>
