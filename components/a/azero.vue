<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfclatj0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:azero" /></template>
<style>
.hfclatj0z {
  fill: var(--svg-color--1d242c, #1d242c);
  fill-rule: evenodd;
  d: path("M10.392 3.424L7.364 10.5H3.203a.204.204 0 0 0-.203.205v1.99c0 .113.09.205.203.205h3.135l-3.214 7.51c-.059.137.04.29.185.29h2.447c.082 0 .155-.05.187-.126l6.03-14.601l5.948 14.6a.2.2 0 0 0 .187.127h2.583a.206.206 0 0 0 .186-.289l-3.19-7.51h3.11a.204.204 0 0 0 .203-.206v-1.99a.204.204 0 0 0-.202-.205h-4.13l-3.006-7.075a.2.2 0 0 0-.186-.125h-2.898a.2.2 0 0 0-.186.124");
}

</style>
