<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aovbt8b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-accessibility" /></template>
<style>
.aovbt8b1a {
  fill: currentColor;
  d: path("M12 2c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m9 7h-6v13h-2v-6h-2v6H9V9H3V7h18z");
}

</style>
