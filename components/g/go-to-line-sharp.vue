<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkz96bi0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:go-to-line-sharp" /></template>
<style>
.fkz96bi0u {
  fill: currentColor;
  d: path("M11 7V5h2v2zm0 12v-2h2v2z");
}

</style>
