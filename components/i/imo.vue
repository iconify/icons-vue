<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t95zvacjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:imo" /></template>
<style>
.t95zvacjd {
  d: path("M13.588 21h-8.47V10.962L13.588 3zm2.647 0V8.538l2.647 2.768V21z");
}

</style>
