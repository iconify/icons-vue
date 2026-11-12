<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ologbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-star-fill-sharp" /></template>
<style>
.j8ologbug {
  fill: currentColor;
  d: path("m7.894 2.953l.966 1.931l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L7 10.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0M21 6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Zm0 10H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2m-4 4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
