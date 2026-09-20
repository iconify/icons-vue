<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yksng_nje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-three-16-filled" /></template>
<style>
.yksng_nje {
  fill: currentColor;
  d: path("M3.473 1.998a1 1 0 0 1 .865-.498h2.324a1 1 0 0 1 .865.498l1.16 2a1 1 0 0 1 0 1.004l-1.16 2a1 1 0 0 1-.865.498H4.338a1 1 0 0 1-.865-.498l-1.16-2a1 1 0 0 1 0-1.004zM4.338 8.5a1 1 0 0 0-.865.498l-1.16 2a1 1 0 0 0 0 1.004l1.16 2a1 1 0 0 0 .865.498h2.324a1 1 0 0 0 .865-.498l1.16-2a1 1 0 0 0 0-1.004l-1.16-2a1 1 0 0 0-.865-.498zm5.135-3.002A1 1 0 0 1 10.338 5h2.324a1 1 0 0 1 .865.498l1.16 2a1 1 0 0 1 0 1.004l-1.16 2a1 1 0 0 1-.865.498h-2.324a1 1 0 0 1-.865-.498l-1.16-2a1 1 0 0 1 0-1.004z");
}

</style>
