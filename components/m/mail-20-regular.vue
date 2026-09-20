<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lkkzpbdeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-20-regular" /></template>
<style>
.lkkzpbdeb {
  fill: currentColor;
  d: path("M15.5 4A2.5 2.5 0 0 1 18 6.5v8a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 2 14.5v-8A2.5 2.5 0 0 1 4.5 4zM17 7.961l-6.746 3.97a.5.5 0 0 1-.426.038l-.082-.038L3 7.963V14.5A1.5 1.5 0 0 0 4.5 16h11a1.5 1.5 0 0 0 1.5-1.5zM15.5 5h-11A1.5 1.5 0 0 0 3 6.5v.302l7 4.118l7-4.12v-.3A1.5 1.5 0 0 0 15.5 5");
}

</style>
