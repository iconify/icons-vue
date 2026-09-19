<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejsolib7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-maximize" /></template>
<style>
.ejsolib7l {
  fill: currentColor;
  d: path("M3 3h18v2H3z");
}

</style>
