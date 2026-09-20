<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3bc16iph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-32-filled" /></template>
<style>
.u3bc16iph {
  fill: currentColor;
  d: path("M6.5 3A1.5 1.5 0 0 0 5 4.5V28a1 1 0 1 0 2 0v-7h21a1 1 0 0 0 .8-1.6L23.25 12l5.55-7.4A1 1 0 0 0 28 3z");
}

</style>
