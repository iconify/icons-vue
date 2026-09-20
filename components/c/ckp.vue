<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aodhidc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ckp" /></template>
<style>
.aodhidc1u {
  fill: var(--svg-color--1fa4ff, #1fa4ff);
  d: path("m12.085 3l7.592 4.405l-3.463 4.537l3.288 4.754L12.085 21l-7.761-4.5v-9zm.71 14.824a5.8 5.8 0 0 0 3.652-1.287l-.98-1.588a4.14 4.14 0 0 1-2.408.757c-2.192 0-3.97-1.657-3.97-3.706s1.778-3.706 3.97-3.706c.847 0 1.63.249 2.277.667l.952-1.62a5.825 5.825 0 1 0-3.494 10.482");
}

</style>
