<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb1wkvb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-bulk-round" /></template>
<style>
.tb1wkvb_c {
  fill: currentColor;
  d: path("m12 12.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

</style>
