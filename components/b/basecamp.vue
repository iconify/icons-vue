<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fpm30vqvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:basecamp" /></template>
<style>
.fpm30vqvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.197C8.917 16.076 14.044 8.19 25.282 8.19S40.594 21.465 42.5 32.835c-5.323 5.257-11.107 6.975-18.485 6.975c-4.985 0-10.957-2.638-15.098-7.37c2.327-4.724 4.585-9.332 7.098-9.332c2.465 0 3.779 4.535 6.112 4.535c3.155 0 5.849-8.741 5.849-8.741");
}

</style>
