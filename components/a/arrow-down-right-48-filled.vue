<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eli3ou6hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-right-48-filled" /></template>
<style>
.eli3ou6hl {
  fill: currentColor;
  d: path("M22.5 42a1.5 1.5 0 0 1 0-3h14.379L6.439 8.56a1.5 1.5 0 1 1 2.122-2.12L39 36.878V22.5a1.5 1.5 0 0 1 3 0v18a1.5 1.5 0 0 1-1.5 1.5z");
}

</style>
