<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c8gdpqbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-48-regular" /></template>
<style>
.c8gdpqbjw {
  fill: currentColor;
  d: path("M25.75 42a1.25 1.25 0 1 0 0-2.5H10.268L41.634 8.134a1.25 1.25 0 0 0-1.768-1.768L8.5 37.732V22.25a1.25 1.25 0 0 0-2.5 0v18.5c0 .69.56 1.25 1.25 1.25z");
}

</style>
