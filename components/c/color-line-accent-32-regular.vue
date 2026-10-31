<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fpm4pkb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-accent-32-regular" /></template>
<style>
.fpm4pkb8a {
  fill: currentColor;
  d: path("M25.5 21a2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-2.5 2.5h-19A2.5 2.5 0 0 1 4 25.5v-2a2.5 2.5 0 0 1 1.509-2.296a2.5 2.5 0 0 0 3.053 2.232l5.94-1.37A4.5 4.5 0 0 0 16.526 21z");
}

</style>
