<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mg-0eml_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-right-28-filled" /></template>
<style>
.mg-0eml_x {
  fill: currentColor;
  d: path("M15.705 4.289a1 1 0 1 0-1.406 1.422L21.675 13H4a1 1 0 1 0 0 2h17.673l-7.374 7.286a1 1 0 0 0 1.406 1.423l8.927-8.821a1.25 1.25 0 0 0 0-1.778z");
}

</style>
