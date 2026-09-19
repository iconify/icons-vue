<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfe20pbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-swap-vertical-circle" /></template>
<style>
.vfe20pbns {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2M6.5 9L10 5.5L13.5 9H11v4H9V9zm11 6L14 18.5L10.5 15H13v-4h2v4z");
}

</style>
