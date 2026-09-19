<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smqyzi5gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-less-than" /></template>
<style>
.smqyzi5gq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 17.5L9.25 12l8.25-5.5l-1-1.5L6 12l10.5 7z");
}

</style>
