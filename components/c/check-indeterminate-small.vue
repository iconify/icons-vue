<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-aohbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-indeterminate-small" /></template>
<style>
.fq-aohbnb {
  fill: currentColor;
  d: path("M7 12.5v-1h10v1z");
}

</style>
