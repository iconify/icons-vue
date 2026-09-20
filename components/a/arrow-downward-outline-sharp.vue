<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9aatyexn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-downward-outline-sharp" /></template>
<style>
.x9aatyexn {
  fill: currentColor;
  d: path("M11.5 5v12.079l-5.792-5.792L5 12l7 7l7-7l-.708-.713l-5.792 5.792V5z");
}

</style>
