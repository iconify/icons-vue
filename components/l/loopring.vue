<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixw6ohbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:loopring" /></template>
<style>
.ixw6ohbxp {
  fill: var(--svg-color--1f63ff, #1f63ff);
  d: path("M8.993 5.117V18.88L3 13.99zm0 13.766l5.654-4.889l-1.645-2.582H21z");
}

</style>
