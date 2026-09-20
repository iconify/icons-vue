<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odo3otbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:graphic-eq-sharp" /></template>
<style>
.odo3otbwc {
  fill: currentColor;
  d: path("M7 18V6h2v12zm4 4V2h2v20zm-8-8v-4h2v4zm12 4V6h2v12zm4-4v-4h2v4z");
}

</style>
