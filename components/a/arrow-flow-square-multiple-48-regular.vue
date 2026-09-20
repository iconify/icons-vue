<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xp6fxh75h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-48-regular" /></template>
<style>
.xp6fxh75h {
  fill: currentColor;
  d: path("M37 13.125c2.853.58 5 3.101 5 6.125v10.5C42 36.516 36.516 42 29.75 42h-10.5a6.25 6.25 0 0 1-6.125-5h2.59a3.75 3.75 0 0 0 3.535 2.5h10.5a9.75 9.75 0 0 0 9.75-9.75v-10.5a3.75 3.75 0 0 0-2.5-3.536zM28.75 6A6.25 6.25 0 0 1 35 12.25v16.5A6.25 6.25 0 0 1 28.75 35h-16.5A6.25 6.25 0 0 1 6 28.75v-8.437a4.25 4.25 0 0 0 2.5 0v8.437a3.75 3.75 0 0 0 3.75 3.75h16.5a3.75 3.75 0 0 0 3.75-3.75v-16.5a3.75 3.75 0 0 0-3.75-3.75h-16.5a3.75 3.75 0 0 0-3.749 3.688a4.25 4.25 0 0 0-2.5-.002A6.25 6.25 0 0 1 12.25 6zm-21.5 8c.78 0 1.467.397 1.871 1h1.496a8.43 8.43 0 0 1 7.054 3.816a5.93 5.93 0 0 0 4.962 2.684h3.1l-3.367-3.366a1.25 1.25 0 0 1 1.768-1.768l5.5 5.5a1.25 1.25 0 0 1 0 1.768l-5.5 5.5a1.25 1.25 0 0 1-1.768-1.768L25.732 24h-3.1a8.43 8.43 0 0 1-7.053-3.816a5.93 5.93 0 0 0-4.962-2.684H9.121A2.25 2.25 0 1 1 7.25 14");
}

</style>
