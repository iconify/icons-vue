<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4pjcuu9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-added-sharp" /></template>
<style>
.o4pjcuu9e {
  fill: currentColor;
  d: path("M17.114 9L15 6.887l.689-.714l1.424 1.425l3.525-3.55l.714.714zM6 19.5V4h7.77q-.386.596-.578 1.197T13 6.5q0 1.742 1.157 3.012T17 10.958q.287.036.5.036t.5-.036V19.5l-6-2.577z");
}

</style>
