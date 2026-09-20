<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o32ra1bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-menu-open" /></template>
<style>
.o32ra1bws {
  fill: currentColor;
  d: path("M9 21V3h2v18zm4-4V7l5 5z");
}

</style>
