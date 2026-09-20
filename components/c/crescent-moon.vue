<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wwksshc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:crescent-moon" /></template>
<style>
.wwksshc1m {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M105.87 14.99A67 67 0 0 0 93.45 6.1c-.87-.49-2-.35-2.71.33s-.83 1.73-.29 2.53c15.63 22.93 12.29 52.52-8.11 71.97c-11.9 11.35-27.85 17.6-44.91 17.6c-11.39 0-22.54-2.86-32.24-8.27c-.87-.49-2-.36-2.71.33c-.71.68-.83 1.72-.28 2.53c2.81 4.12 6.12 7.93 9.86 11.32c12.61 11.45 29.27 17.76 46.9 17.76c18.27 0 35.34-6.7 48.09-18.86c12.53-11.94 19.31-27.71 19.09-44.4s-7.42-32.3-20.27-43.95");
}

</style>
