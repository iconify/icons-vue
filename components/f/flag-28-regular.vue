<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tqsc_poch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-28-regular" /></template>
<style>
.tqsc_poch {
  fill: currentColor;
  d: path("M5.5 16.5v-12h16.392l-3.527 5.6a.75.75 0 0 0 0 .8l3.527 5.6zm0 1.5h17.75c.59 0 .95-.65.635-1.15l-3.999-6.35l3.999-6.35A.75.75 0 0 0 23.25 3H4.75a.75.75 0 0 0-.75.75v20.5a.75.75 0 0 0 1.5 0z");
}

</style>
