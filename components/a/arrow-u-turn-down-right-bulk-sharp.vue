<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vym892b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-right-bulk-sharp" /></template>
<style>
.vym892b2t {
  fill: currentColor;
  d: path("m21.707 15.707l-4 4a.999.999 0 1 1-1.414-1.414L18.586 16H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h10a1 1 0 0 1 0 2H4v8h14.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414");
}

</style>
