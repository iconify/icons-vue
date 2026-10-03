<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0kdc69os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-2-fill" /></template>
<style>
.d0kdc69os {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 4C7 2.3431 8.3431 1 10 1L14 1C15.6569 1 17 2.3431 17 4L17 8C17 9.6569 15.6569 11 14 11L10 11C8.3431 11 7 9.6569 7 8L7 4ZM1 16C1 14.3431 2.3431 13 4 13L8 13C9.6569 13 11 14.3431 11 16L11 20C11 21.6569 9.6569 23 8 23L4 23C2.3431 23 1 21.6569 1 20L1 16ZM13 16C13 14.3431 14.3431 13 16 13L20 13C21.6569 13 23 14.3431 23 16L23 20C23 21.6569 21.6569 23 20 23L16 23C14.3431 23 13 21.6569 13 20L13 16Z");
}

</style>
