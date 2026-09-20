<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5qai4-cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-french" /></template>
<style>
.d5qai4-cq {
  fill: currentColor;
  d: path("M4 17V7h7v2H6v2h4v2H6v4zm9 0V7h5q.825 0 1.413.588T20 9v2q0 .8-.55 1.363t-1.3.637L20 17h-2.1l-1.875-4H15v4zm2-6h3V9h-3z");
}

</style>
