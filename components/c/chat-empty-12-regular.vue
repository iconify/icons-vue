<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ke0sflhyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-empty-12-regular" /></template>
<style>
.ke0sflhyo {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 2.59 4.382l-1.944.592a.5.5 0 0 1-.624-.624l.592-1.947A5 5 0 0 1 1 6m5-4a4 4 0 0 0-3.417 6.08a.5.5 0 0 1 .051.406l-.383 1.259l1.257-.383a.5.5 0 0 1 .407.052A4 4 0 1 0 6 2");
}

</style>
