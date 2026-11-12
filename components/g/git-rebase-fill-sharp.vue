<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlxo-db1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-rebase-fill-sharp" /></template>
<style>
.nlxo-db1u {
  fill: currentColor;
  d: path("M7.829 5h8.342a3 3 0 1 1 0 2H7.829A3.01 3.01 0 0 1 6 8.829v6.342a3 3 0 1 1-2 0V8.829A3 3 0 1 1 7.829 5M19 12a1 1 0 0 1 1 1v8a1 1 0 0 1-2 0v-7h-4.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L13.414 12Z");
}

</style>
