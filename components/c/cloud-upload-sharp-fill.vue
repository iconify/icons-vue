<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vx1py7b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-upload-sharp-fill" /></template>
<style>
.vx1py7b8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 20C3.3767 20 1 17.6233 1 15C1 12.6937 2.837 10.578 5.0635 10.1004C5.5356 6.7612 8.5755 4 12 4C15.4245 4 18.4644 6.7612 18.9365 10.1004C21.163 10.578 23 12.6937 23 15C23 17.6233 20.6233 20 18 20L6 20ZM13 12.6642L13.8358 13.5L15.25 12.0858L12.7071 9.5429C12.5196 9.3554 12.2652 9.25 12 9.25C11.7348 9.25 11.4804 9.3554 11.2929 9.5429L8.75 12.0858L10.1642 13.5L11 12.6642L11 15.75L13 15.75L13 12.6642Z");
}

</style>
