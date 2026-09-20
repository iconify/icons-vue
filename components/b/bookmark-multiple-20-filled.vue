<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3vr8sqws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-multiple-20-filled" /></template>
<style>
.j3vr8sqws {
  fill: currentColor;
  d: path("M6.268 3A2 2 0 0 1 8 2h4.5A3.5 3.5 0 0 1 16 5.5v10a.5.5 0 0 1-.777.416L15 15.768V5.5A2.5 2.5 0 0 0 12.5 3zM6 4a2 2 0 0 0-2 2v11.5a.5.5 0 0 0 .777.416L9 15.101l4.223 2.815A.5.5 0 0 0 14 17.5V6a2 2 0 0 0-2-2z");
}

</style>
