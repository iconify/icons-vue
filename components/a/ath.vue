<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rta4fyaty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ath" /></template>
<style>
.rta4fyaty {
  fill: var(--svg-color--ea6e25, #ea6e25);
  d: path("M15.706 21h-2.393L12 5.758L10.687 21H8.294l2.17-18h3.077z");
}

</style>
