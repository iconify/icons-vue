<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x2crpubqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-48-filled" /></template>
<style>
.x2crpubqo {
  fill: currentColor;
  d: path("M30.56 26.56a1.5 1.5 0 0 1-2.12-2.12L34.877 18H17.5a4.5 4.5 0 0 0-4.5 4.5v18a1.5 1.5 0 1 1-3 0v-18a7.5 7.5 0 0 1 7.5-7.5h17.38l-6.44-6.44a1.5 1.5 0 0 1 2.12-2.12l9 9a1.5 1.5 0 0 1 0 2.12z");
}

</style>
