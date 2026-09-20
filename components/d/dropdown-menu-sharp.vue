<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q39d-0mav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dropdown-menu-sharp" /></template>
<style>
.q39d-0mav {
  fill: currentColor;
  d: path("M14.5 14.5L18 11h-7zM8 19q-2.925 0-4.962-2.037T1 12t2.038-4.962T8 5h8q2.925 0 4.963 2.038T23 12t-2.037 4.963T16 19z");
}

</style>
