<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="idubya14c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-down-48-filled" /></template>
<style>
.idubya14c {
  fill: currentColor;
  d: path("M10.894 39.057a1.5 1.5 0 1 1-2.787-1.113L20.702 6.392c.83-2.078 3.76-2.104 4.627-.042l12.293 29.258l3.513-7.728a1.5 1.5 0 0 1 2.73 1.241l-5 11a1.5 1.5 0 0 1-1.942.764l-12-5a1.5 1.5 0 1 1 1.154-2.77l8.781 3.66L23.036 8.637z");
}

</style>
