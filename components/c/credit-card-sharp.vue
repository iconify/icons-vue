<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uamwjmobc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-card-sharp" /></template>
<style>
.uamwjmobc {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-8h16V8H4z");
}

</style>
