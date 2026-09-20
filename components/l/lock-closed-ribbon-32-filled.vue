<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eww0h3bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-32-filled" /></template>
<style>
.eww0h3bdd {
  fill: currentColor;
  d: path("M29 30a1 1 0 0 1-1.528.849L24.5 29l-2.972 1.849A1 1 0 0 1 20 30v-4.138a6.97 6.97 0 0 0 4.5 1.638a6.97 6.97 0 0 0 4.5-1.638zM16 2a6 6 0 0 1 6 6v3.028a4.5 4.5 0 0 1 3.57 2.553a7 7 0 0 0-7.966 5.72a1.75 1.75 0 1 0-.093 1.579a7 7 0 0 0 .989 3.227V29h-8A4.5 4.5 0 0 1 6 24.5v-9a4.5 4.5 0 0 1 4-4.472V8a6 6 0 0 1 6-6m8.5 13a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M16 4a4 4 0 0 0-4 4v3h8V8a4 4 0 0 0-4-4");
}

</style>
