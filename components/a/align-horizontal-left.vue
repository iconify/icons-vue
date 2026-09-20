<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-_embbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-horizontal-left" /></template>
<style>
.fz-_embbz {
  fill: currentColor;
  d: path("M2 22V2h2v20zm4-5v-3h10v3zm0-7V7h16v3z");
}

</style>
