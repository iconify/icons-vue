<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfhfmbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atri" /></template>
<style>
.rdfhfmbbz {
  fill: var(--svg-color--e01920, #e01920);
  d: path("M9 5.25h1.5v3c0 4-.945 9.405-7.5 10.5v-2c1.5-.25 5.985-2 5.985-8.5zm2 0h2v13.5h-2zm4 0h-1.5v3c0 4 .945 9.405 7.5 10.5v-2c-1.5-.25-5.985-2-5.985-8.5z");
}

</style>
