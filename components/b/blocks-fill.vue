<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlm4s4s0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-fill" /></template>
<style>
.hlm4s4s0v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 7C2 5.3431 3.3431 4 5 4L7 4C8.6569 4 10 5.3431 10 7L10 9C10 10.6569 8.6569 12 7 12L5 12C3.3431 12 2 10.6569 2 9L2 7ZM2 17C2 15.3431 3.3431 14 5 14L7 14C8.6569 14 10 15.3431 10 17L10 19C10 20.6569 8.6569 22 7 22L5 22C3.3431 22 2 20.6569 2 19L2 17ZM12 17C12 15.3431 13.3431 14 15 14L17 14C18.6569 14 20 15.3431 20 17L20 19C20 20.6569 18.6569 22 17 22L15 22C13.3431 22 12 20.6569 12 19L12 17ZM14 5C14 3.3431 15.3431 2 17 2L19 2C20.6569 2 22 3.3431 22 5L22 7C22 8.6569 20.6569 10 19 10L17 10C15.3431 10 14 8.6569 14 7L14 5Z");
}

</style>
