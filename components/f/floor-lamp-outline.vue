<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl1pjnbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:floor-lamp-outline" /></template>
<style>
.pl1pjnbdm {
  fill: currentColor;
  d: path("M11 19v-8H6q-.5 0-.8-.4t-.15-.9L7 3.4q.2-.625.725-1.013T8.9 2h6.2q.65 0 1.175.388T17 3.4l1.95 6.3q.15.5-.15.9t-.8.4h-5v8zM7.35 9h9.3L15.1 4H8.9zM8 22v-2h8v2zm4-15.5");
}

</style>
