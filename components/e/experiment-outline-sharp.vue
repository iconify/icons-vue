<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5jrxg-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:experiment-outline-sharp" /></template>
<style>
.pq5jrxg-j {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H7V3h10v2h-2v6l5.55 6.75q.8.975.263 2.113T19 21zm2-3h10l-3.4-4h-3.2zm-2 1h14l-6-7.3V5h-2v6.7zm7-7");
}

</style>
