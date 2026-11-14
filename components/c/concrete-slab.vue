<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alftuq2px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:concrete-slab" /></template>
<style>
.alftuq2px {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 8.25h-3.5V7.5q0-2.75-2.75-2.75T4.75 7.5v.761q-3 .182-3 3.364v4.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-4.75q0-3.182-3-3.364V7.5q0-2.75-2.75-2.75T13.75 7.5zm1.5 0h2.5V7.5q0-1.25-1.25-1.25T15.25 7.5zm-6.5-.75v.75h-2.5V7.5q0-1.25 1.25-1.25T8.75 7.5");
}

</style>
