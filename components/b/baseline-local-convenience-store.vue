<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knkx5hbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-local-convenience-store" /></template>
<style>
.knkx5hbze {
  fill: currentColor;
  d: path("M19 7V4H5v3H2v13h8v-4h4v4h8V7zm-8 3H9v1h2v1H8V9h2V8H8V7h3zm5 2h-1v-2h-2V7h1v2h1V7h1z");
}

</style>
