<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgme79-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-color" /></template>
<style>
.mgme79-hp {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm2-6v-4.25L15.2 2.575q.275-.275.638-.425T16.6 2t.775.15t.675.45L19.425 4q.3.275.438.65t.137.775q0 .375-.137.738t-.438.662L8.25 18zM16.6 6.8L18 5.4L16.6 4l-1.4 1.4z");
}

</style>
