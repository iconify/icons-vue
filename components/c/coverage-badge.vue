<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6ab75nve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coverage-badge" /></template>
<style>
.n6ab75nve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.263 4.798l-8-3Q12.136 1.75 12 1.75t-.263.048l-8 3q-.108.04-.198.11t-.155.165t-.1.203q-.034.109-.034.224V11q0 7.432 8.445 11.185q.146.065.305.065t.305-.065Q20.75 18.432 20.75 11V5.5q0-.115-.034-.224t-.1-.203q-.065-.094-.155-.165q-.09-.07-.198-.11");
}

</style>
