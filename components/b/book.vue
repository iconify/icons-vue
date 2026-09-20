<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="q5p36befo"/><path class="nppdo5v7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:book" /></template>
<style>
.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.nppdo5v7m {
  d: path("M20 5a2 2 0 0 0-2.323-1.974L9.838 4.31A1 1 0 0 0 9 5.297V17a1 1 0 0 0 1.155.988l8.154-1.276A2 2 0 0 0 20 14.737zm-2 9.737l-7 1.094V6.147L18 5z");
}

.q5p36befo {
  d: path("M11 5.297a1 1 0 0 0-.838-.987L2.323 3.026A2 2 0 0 0 0 5v9.737a2 2 0 0 0 1.69 1.975l8.155 1.276A1 1 0 0 0 11 17zm-9 9.44V5l7 1.147v9.684z");
}

</style>
