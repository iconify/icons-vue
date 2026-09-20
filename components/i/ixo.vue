<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m4ojjxbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ixo" /></template>
<style>
.m4ojjxbez {
  fill: var(--svg-color--00d2ff, #00d2ff);
  fill-rule: evenodd;
  d: path("M4.385 9.462a1.385 1.385 0 1 0 0-2.77a1.385 1.385 0 0 0 0 2.77m1.384.461H3v7.385h2.77zm.462 1.902V9.923h1.823l1.869 1.855l1.846-1.855h1.846v1.851l-1.837 1.85l1.837 1.828v1.856h-1.869l-1.818-1.81l-1.796 1.81H6.231v-1.819l1.832-1.841zM21 13.615a3.692 3.692 0 1 1-7.384 0a3.692 3.692 0 0 1 7.384 0m-2.308 0a1.385 1.385 0 1 1-2.769 0a1.385 1.385 0 0 1 2.77 0");
}

</style>
