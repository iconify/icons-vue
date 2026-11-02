<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alvyp9n1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-small-bulk" /></template>
<style>
.alvyp9n1f {
  fill: currentColor;
  d: path("M14.586 13H7a1 1 0 0 1 0-2h7.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

</style>
