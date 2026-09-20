<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ruzpfqbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-20-filled" /></template>
<style>
.ruzpfqbka {
  fill: currentColor;
  d: path("M10.5 17H14a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3h-3.5zm-1-14H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h3.5z");
}

</style>
