<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze9-z_csk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-heart-24-regular" /></template>
<style>
.ze9-z_csk {
  fill: currentColor;
  d: path("M18 20.5a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5v7.31a4.5 4.5 0 0 0-1.5-.075V4a2 2 0 0 1 2-2h6.172c.515 0 1.047.22 1.413.586l5.829 5.828A2 2 0 0 1 20 9.828V20a2 2 0 0 1-2 2H9.49l1.5-1.5zm-.622-12L13.5 4.621V8a.5.5 0 0 0 .5.5zM6.484 22.53a.747.747 0 0 0 1.06 0l4.409-4.408a3.467 3.467 0 1 0-4.903-4.903l-.036.036l-.036-.036a3.467 3.467 0 1 0-4.902 4.903z");
}

</style>
