<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uayz85viw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chats-thin" /></template>
<style>
.uayz85viw {
  fill: currentColor;
  d: path("M216 84h-36V48a12 12 0 0 0-12-12H40a12 12 0 0 0-12 12v128a4 4 0 0 0 4 4a4 4 0 0 0 2.51-.89L73 148h3v36a12 12 0 0 0 12 12h95l38.49 31.11a4 4 0 0 0 2.51.89a4 4 0 0 0 4-4V96a12 12 0 0 0-12-12M71.58 140a4 4 0 0 0-2.51.89L36 167.62V48a4 4 0 0 1 4-4h128a4 4 0 0 1 4 4v88a4 4 0 0 1-4 4ZM220 215.62l-33.07-26.73a4 4 0 0 0-2.51-.89H88a4 4 0 0 1-4-4v-36h84a12 12 0 0 0 12-12V92h36a4 4 0 0 1 4 4Z");
}

</style>
