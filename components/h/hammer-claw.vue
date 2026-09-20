<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="a67ybdblp"/><path class="yrr0f-b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:hammer-claw" /></template>
<style>
.a67ybdblp {
  d: path("M8.632 1.703a2 2 0 0 1 1.088.179l3.808 1.802a2 2 0 0 1 .952 2.664l-1.07 2.26a2 2 0 0 1-2.663.952L7.405 7.978a2 2 0 0 1-.859-.778l-.35-.583l-.95.339c-1.677.6-3.243-1.128-2.48-2.739l.44-.932a2 2 0 0 1 1.576-1.131zm4.04 3.79L8.864 3.69l-3.85.45l-.44.933l.949-.34a2 2 0 0 1 2.388.854l.35.583l3.342 1.582z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.yrr0f-b5p {
  d: path("M13.79 5.468a2 2 0 0 1 2.663-.952l.904.428a2 2 0 0 1 .952 2.663l-1.71 3.616a2 2 0 0 1-2.664.952l-.904-.428a2 2 0 0 1-.952-2.663zm2.712 1.284l-.904-.428l-1.712 3.615l.904.428zm-7.349 1.5l-3.85 8.135l.904.428l3.85-8.135l1.808.856l-3.85 8.134a2 2 0 0 1-2.664.952l-.904-.427a2 2 0 0 1-.952-2.664l3.85-8.135z");
}

</style>
