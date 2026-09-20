<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6pn83ldl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:games-48-filled" /></template>
<style>
.q6pn83ldl {
  fill: currentColor;
  d: path("M18 10c-7.732 0-14 6.268-14 14s6.268 14 14 14h12c7.732 0 14-6.268 14-14s-6.268-14-14-14zm-1.75 8c.69 0 1.25.56 1.25 1.25V23h3.25a1.25 1.25 0 1 1 0 2.5H17.5v3.25a1.25 1.25 0 1 1-2.5 0V25.5h-3.75a1.25 1.25 0 1 1 0-2.5H15v-3.75c0-.69.56-1.25 1.25-1.25M32 27.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m1.5-4.5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
