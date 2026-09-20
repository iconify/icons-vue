<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kns7b3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-rotate-light" /></template>
<style>
.kns7b3bax {
  fill: currentColor;
  d: path("m204.24 220.24l-24 24a6 6 0 0 1-8.48-8.48L185.51 222H80a22 22 0 0 1-22-22v-96a6 6 0 0 1 12 0v96a10 10 0 0 0 10 10h105.51l-13.75-13.76a6 6 0 0 1 8.48-8.48l24 24a6 6 0 0 1 0 8.48M80 70a6 6 0 0 0 4.24-10.24L70.49 46H176a10 10 0 0 1 10 10v96a6 6 0 0 0 12 0V56a22 22 0 0 0-22-22H70.49l13.75-13.76a6 6 0 0 0-8.48-8.48l-24 24a6 6 0 0 0 0 8.48l24 24A6 6 0 0 0 80 70");
}

</style>
