<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jm1__ubko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-28-filled" /></template>
<style>
.jm1__ubko {
  fill: currentColor;
  d: path("M11.5 4c.98 0 1.865.402 2.5 1.05A3.5 3.5 0 0 1 16.5 4H24a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-7.5a3.5 3.5 0 0 1-2.5-1.05A3.5 3.5 0 0 1 11.5 24H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zM13 20.5v-13A1.5 1.5 0 0 0 11.5 6H4v16h7.5a1.5 1.5 0 0 0 1.5-1.5m2-13v13a1.5 1.5 0 0 0 1.5 1.5H24V6h-7.5A1.5 1.5 0 0 0 15 7.5");
}

</style>
