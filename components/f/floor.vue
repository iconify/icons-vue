<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1re1x9eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:floor" /></template>
<style>
.s1re1x9eu {
  fill: var(--svg-color--00f3d5, #00f3d5);
  d: path("M3 10.941h18v2.118H3z");
}

</style>
