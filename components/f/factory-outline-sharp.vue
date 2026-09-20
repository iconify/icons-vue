<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmg3jnb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:factory-outline-sharp" /></template>
<style>
.cmg3jnb3j {
  fill: currentColor;
  d: path("M2 22V9.975L9 7v2l5-2v3h8v12zm2-2h16v-8h-8V9.95l-5 2V10l-3 1.325zm7-2h2v-4h-2zm-4 0h2v-4H7zm8 0h2v-4h-2zm7-8h-5l1-8h3zM4 20h16z");
}

</style>
