<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iadiydzyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-down-left-48-filled" /></template>
<style>
.iadiydzyj {
  fill: currentColor;
  d: path("M35 7.5a1.5 1.5 0 0 1 3 0v18a7.5 7.5 0 0 1-7.5 7.5H13.121l6.44 6.44a1.5 1.5 0 0 1-2.122 2.12l-9-9a1.5 1.5 0 0 1 0-2.12l9-9a1.5 1.5 0 0 1 2.122 2.12L13.12 30H30.5a4.5 4.5 0 0 0 4.5-4.5z");
}

</style>
