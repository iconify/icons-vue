<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":257,"height":256};
const content = `<path class="gsrc_2l_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:forest-icon" /></template>
<style>
.gsrc_2l_u {
  fill: var(--svg-color--3f5b1e, #3f5b1e);
  d: path("M.16.002v256h115.6V153.883l-49.874 49.874l-17.525-17.528l79.803-79.815l79.81 79.815l-17.524 17.528l-49.874-49.874v102.119H256.16v-256zm190.258 134.85L128.14 72.565l-62.278 62.287l-17.525-17.527L128.14 37.5l79.81 79.824z");
}

</style>
