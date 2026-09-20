<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o6ui0_l3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:glance-horizontal-20-filled" /></template>
<style>
.o6ui0_l3j {
  fill: currentColor;
  d: path("M14.5 3h1A1.5 1.5 0 0 1 17 4.5v3A1.5 1.5 0 0 1 15.5 9h-1A1.5 1.5 0 0 1 13 7.5v-3A1.5 1.5 0 0 1 14.5 3m-10 0h5A1.5 1.5 0 0 1 11 4.5v3A1.5 1.5 0 0 1 9.5 9h-5A1.5 1.5 0 0 1 3 7.5v-3A1.5 1.5 0 0 1 4.5 3m0 8h1A1.5 1.5 0 0 1 7 12.5v3A1.5 1.5 0 0 1 5.5 17h-1A1.5 1.5 0 0 1 3 15.5v-3A1.5 1.5 0 0 1 4.5 11M9 12.5a1.5 1.5 0 0 1 1.5-1.5h5a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 9 15.5z");
}

</style>
