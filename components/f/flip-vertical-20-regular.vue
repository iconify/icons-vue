<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ea7x1hbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-20-regular" /></template>
<style>
.ea7x1hbky {
  fill: currentColor;
  d: path("M15.77 2.079A.5.5 0 0 1 16 2.5v6a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.21-.954l13-6a.5.5 0 0 1 .48.033M4.777 8H15V3.281zM16 17.5a.5.5 0 0 1-.71.454l-13-6A.5.5 0 0 1 2.5 11h13a.5.5 0 0 1 .5.5z");
}

</style>
