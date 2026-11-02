<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3-qm3p0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-fill-sharp" /></template>
<style>
.o3-qm3p0p {
  fill: currentColor;
  d: path("M11 10.3V7a1 1 0 0 1 1.486-.874l9 5a1 1 0 0 1 0 1.748l-9 5A1 1 0 0 1 11 17v-3.3l-7.514 4.174A1 1 0 0 1 2 17V7a1 1 0 0 1 1.486-.874Z");
}

</style>
