<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nzi93pydh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-between-fill" /></template>
<style>
.nzi93pydh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1C4.5523 1 5 1.4477 5 2V6.1716C5.3212 6.058 5.6593 6 6 6H7C8.6569 6 10 7.3431 10 9V15C10 16.6569 8.6569 18 7 18H6C5.6593 18 5.3212 17.942 5 17.8284V22C5 22.5523 4.5523 23 4 23C3.4477 23 3 22.5523 3 22V2C3 1.4477 3.4477 1 4 1ZM20 1C19.4477 1 19 1.4477 19 2V6.1716C18.6788 6.058 18.3407 6 18 6H17C15.3431 6 14 7.3431 14 9V15C14 16.6569 15.3431 18 17 18H18C18.3407 18 18.6788 17.942 19 17.8284V22C19 22.5523 19.4477 23 20 23C20.5523 23 21 22.5523 21 22V2C21 1.4477 20.5523 1 20 1Z");
}

</style>
