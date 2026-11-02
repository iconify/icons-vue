<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y63fkab4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-fill" /></template>
<style>
.y63fkab4n {
  fill: currentColor;
  d: path("M7.107 5.963a5.001 5.001 0 0 1 9.786 0a4.94 4.94 0 0 1 2.735.971c.955.718 1.622 1.776 1.911 2.931c.582 2.332-.391 4.666-2.539 5.783V16H5v-.352c-2.148-1.117-3.121-3.451-2.539-5.783c.289-1.155.956-2.213 1.911-2.931a4.94 4.94 0 0 1 2.735-.971M5 19v-1h14v1a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3");
}

</style>
