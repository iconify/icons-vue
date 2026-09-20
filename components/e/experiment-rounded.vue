<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxxl_rj9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:experiment-rounded" /></template>
<style>
.zxxl_rj9s {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H8q-.425 0-.712-.288T7 4t.288-.712T8 3h8q.425 0 .713.288T17 4t-.288.713T16 5h-1v6l5.55 6.75q.8.975.263 2.113T19 21zm2-3h10l-3.4-4h-3.2z");
}

</style>
