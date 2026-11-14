<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejvvuibyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-accent-32-light" /></template>
<style>
.ejvvuibyg {
  fill: currentColor;
  d: path("M25.5 20a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5h-19A3.5 3.5 0 0 1 3 25.5v-2a3.5 3.5 0 0 1 2.64-3.395l-.076.332a2.5 2.5 0 0 0 2.999 2.999l5.94-1.37a4.5 4.5 0 0 0 2.17-1.204l.863-.862z");
}

</style>
