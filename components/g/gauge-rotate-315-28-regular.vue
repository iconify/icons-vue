<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g4nqodbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-28-regular" /></template>
<style>
.g4nqodbow {
  fill: currentColor;
  d: path("M14.797 2.026C21.053 2.436 26 7.64 26 13.999c0 6.628-5.373 12-12 12S2 20.627 2 14a11.97 11.97 0 0 1 3.735-8.7a.75.75 0 0 1 1.034 1.088A10.47 10.47 0 0 0 3.5 13.999c0 5.8 4.701 10.5 10.5 10.5S24.5 19.8 24.5 14c0-5.564-4.329-10.118-9.802-10.477a.75.75 0 1 1 .099-1.496M7.862 9.24c-.573-.878.41-1.906 1.295-1.43l.085.05c1.938 1.276 3.889 2.537 5.782 3.88c.484.342.912.658 1.098.844a2.501 2.501 0 0 1-3.535 3.536c-.186-.186-.503-.614-.846-1.098c-1.089-1.536-2.914-4.308-3.879-5.782");
}

</style>
