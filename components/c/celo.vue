<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k53vtabkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:celo" /></template>
<style>
.k53vtabkp {
  fill: var(--svg-color--fcfe52, #fcfe52);
  d: path("M3 3h18v6.429h-3.111a6.428 6.428 0 1 0 0 5.143H21V21H3z");
}

</style>
