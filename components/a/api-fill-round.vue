<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0zulnbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:api-fill-round" /></template>
<style>
.l0zulnbdn {
  fill: currentColor;
  d: path("M7.707 8.707L4.414 12l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414m10-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414L19.586 12l-3.293-3.293a.999.999 0 1 1 1.414-1.414M10 11h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
