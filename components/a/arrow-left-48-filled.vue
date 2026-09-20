<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f9serjbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-48-filled" /></template>
<style>
.f9serjbif {
  fill: currentColor;
  d: path("M44.25 24a1.5 1.5 0 0 1-1.5 1.5H10.915l12.387 12.18a1.5 1.5 0 1 1-2.104 2.14L6.201 25.072l-.02-.02a1.5 1.5 0 0 1 .042-2.145L21.198 8.18a1.5 1.5 0 1 1 2.104 2.14L10.915 22.5H42.75a1.5 1.5 0 0 1 1.5 1.5");
}

</style>
