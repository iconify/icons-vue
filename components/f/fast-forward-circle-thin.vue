<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qz73eqb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:fast-forward-circle-thin" /></template>
<style>
.qz73eqb8z {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m62.4-95.2l-48-36A4 4 0 0 0 136 92v72a4 4 0 0 0 2.21 3.58a4.05 4.05 0 0 0 1.79.42a4 4 0 0 0 2.4-.8l48-36a4 4 0 0 0 0-6.4M144 156v-56l37.33 28Zm-9.6-31.2l-48-36A4 4 0 0 0 80 92v72a4 4 0 0 0 2.21 3.58A4.05 4.05 0 0 0 84 168a4 4 0 0 0 2.4-.8l48-36a4 4 0 0 0 0-6.4M88 156v-56l37.33 28Z");
}

</style>
