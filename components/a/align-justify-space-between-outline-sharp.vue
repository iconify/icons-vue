<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvkgekbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-space-between-outline-sharp" /></template>
<style>
.cvkgekbcz {
  fill: currentColor;
  d: path("M20 22v-5h-3V7h3V2h2v20zM2 22V2h2v5h3v10H4v5z");
}

</style>
