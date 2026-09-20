<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7sn1cb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-arrow" /></template>
<style>
.t7sn1cb0u {
  fill: currentColor;
  d: path("M11 19v-6H2v-2h9V5l11 7z");
}

</style>
