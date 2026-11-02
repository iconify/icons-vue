<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw4nc3bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-up-right-fill-round" /></template>
<style>
.kw4nc3bke {
  fill: currentColor;
  d: path("M14.586 9H11a3 3 0 0 0-3 3v9a1 1 0 0 1-2 0v-9a5 5 0 0 1 5-5h3.586l-3.293-3.293a.999.999 0 1 1 1.414-1.414l5 5a1 1 0 0 1 0 1.414l-5 5a.999.999 0 1 1-1.414-1.414Z");
}

</style>
