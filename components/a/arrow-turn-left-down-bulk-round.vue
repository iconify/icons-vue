<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfj06-b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-left-down-bulk-round" /></template>
<style>
.cfj06-b1z {
  fill: currentColor;
  d: path("M12 8a3 3 0 0 0-3 3v3.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-5 5a1 1 0 0 1-1.414 0l-5-5a.999.999 0 1 1 1.414-1.414L7 14.586V11a5 5 0 0 1 5-5h9a1 1 0 0 1 0 2Z");
}

</style>
