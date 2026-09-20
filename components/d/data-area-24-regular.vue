<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1t8r4s4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-area-24-regular" /></template>
<style>
.l1t8r4s4u {
  fill: currentColor;
  d: path("M3.75 3a.75.75 0 0 1 .75.75v6.258l3.65-1.922a.75.75 0 0 1 .73.018l3.82 2.246l5.6-4.2a.75.75 0 0 1 1.2.6V19.5h.75a.75.75 0 0 1 0 1.5h-14A3.25 3.25 0 0 1 3 17.75v-14A.75.75 0 0 1 3.75 3M18 19.5V8.25l-4.8 3.6a.75.75 0 0 1-.83.046L8.48 9.609L4.5 11.703v6.047c0 .966.784 1.75 1.75 1.75z");
}

</style>
