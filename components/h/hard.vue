<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8sx_kbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hard" /></template>
<style>
.i8sx_kbfb {
  fill: var(--svg-color--441f67, #441f67);
  d: path("M4.385 3h3.461v6.923h8.308V3h3.462v18h-3.462v-7.615H7.846V21H4.385z");
}

</style>
