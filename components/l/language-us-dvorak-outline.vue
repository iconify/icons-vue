<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w76gw5bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-us-dvorak-outline" /></template>
<style>
.w76gw5bno {
  fill: currentColor;
  d: path("M6 15h3.25V9H6zm-2 2V7h5.25q.825 0 1.413.588T11.25 9v6q0 .825-.587 1.413T9.25 17zm11.625 0L12.25 7h2l2.375 6.95L19 7h2l-3.375 10z");
}

</style>
