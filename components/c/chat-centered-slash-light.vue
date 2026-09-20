<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qsj9j4bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-centered-slash-light" /></template>
<style>
.qsj9j4bmi {
  fill: currentColor;
  d: path("M52.44 36a6 6 0 0 0-10.1 6H40a14 14 0 0 0-14 14v128a14 14 0 0 0 14 14h61.59l14.25 25a14 14 0 0 0 24.32 0l14.25-25h29.12l20 22a6 6 0 0 0 8.88-8.08Zm98.49 150a6 6 0 0 0-5.21 3l-16 28a2 2 0 0 1-3.48 0l-16-28a6 6 0 0 0-5.21-3H40a2 2 0 0 1-2-2V56a2 2 0 0 1 2-2h12.62l120 132ZM230 56v130a6 6 0 0 1-12 0V56a2 2 0 0 0-2-2H98.52a6 6 0 1 1 0-12H216a14 14 0 0 1 14 14");
}

</style>
