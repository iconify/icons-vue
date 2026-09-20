<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb5h8sbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ambient-screen-sharp" /></template>
<style>
.mb5h8sbzh {
  fill: currentColor;
  d: path("m12 16l1.25-2.75L16 12l-2.75-1.25L12 8l-1.25 2.75L8 12l2.75 1.25L12 16Zm7.5 5l-1.1-2.4l-2.4-1.1l2.4-1.1l1.1-2.4l1.1 2.4l2.4 1.1l-2.4 1.1l-1.1 2.4ZM2 20V4h20v9.175q-.575-.35-1.213-.513T19.5 12.5q-2.075 0-3.538 1.463T14.5 17.5q0 .65.163 1.288T15.175 20H2Z");
}

</style>
