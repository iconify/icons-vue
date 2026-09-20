<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6stp4bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-48-filled" /></template>
<style>
.y6stp4bro {
  fill: currentColor;
  d: path("M22.5 6a1.5 1.5 0 0 0 0 3h14.379l-6.44 6.44a1.5 1.5 0 0 0 2.122 2.12L39 11.122V25.5a1.5 1.5 0 0 0 3 0v-18A1.5 1.5 0 0 0 40.5 6zm-5.94 27.56a1.5 1.5 0 0 0-2.12-2.12l-8 8a1.5 1.5 0 0 0 2.12 2.12zm12-14.12a1.5 1.5 0 0 1 0 2.12l-8 8a1.5 1.5 0 0 1-2.12-2.12l8-8a1.5 1.5 0 0 1 2.12 0");
}

</style>
