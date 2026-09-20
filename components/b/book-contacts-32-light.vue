<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xbvjvt1lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-contacts-32-light" /></template>
<style>
.xbvjvt1lh {
  fill: currentColor;
  d: path("M23 2a4 4 0 0 1 4 4v18a2 2 0 0 1-2 2H6a3 3 0 0 0 3 3h17.5a.5.5 0 0 1 0 1H9a4 4 0 0 1-4-4V6a4 4 0 0 1 4-4zM9 3a3 3 0 0 0-3 3v19h19a1 1 0 0 0 1-1V6a3 3 0 0 0-3-3zm10.454 12c1.13 0 2.046.915 2.046 2.045v.205c0 1.868-1.571 3.75-5.5 3.75s-5.5-1.875-5.5-3.75v-.205c0-1.13.916-2.045 2.046-2.045zM16 7.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6");
}

</style>
