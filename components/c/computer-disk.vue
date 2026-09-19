<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mixx50prw"/><path class="df8x_ibvh"/><path class="jsmx8-fmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:computer-disk" /></template>
<style>
.df8x_ibvh {
  fill: var(--svg-color--ede0ba, #ede0ba);
  d: path("M32.05 3.827c-15.881 0-28.756 12.875-28.756 28.756c0 15.886 12.875 28.761 28.756 28.761c15.886 0 28.762-12.875 28.762-28.761c0-15.881-12.875-28.756-28.762-28.756m0 38.42a8.917 8.917 0 1 1 8.919-8.917a8.917 8.917 0 0 1-8.919 8.917");
}

.jsmx8-fmu {
  fill: var(--svg-color--c8bc9e, #c8bc9e);
  d: path("M40.971 33.32c0 2.271-.876 4.322-2.274 5.895a410 410 0 0 0 15.24 12a28.63 28.63 0 0 0 4.809-29.302c-6.312 2.352-12.449 5.04-18.623 7.666a8.85 8.85 0 0 1 .848 3.741");
}

.mixx50prw {
  fill: var(--svg-color--243438, #243438);
  d: path("M.942 62.899h62.22c.514 0 .942-.422.942-.918V2.916c0-.499-.427-.916-.941-.916H.943C.665 2 .45 2.094.3 2.246c-.007 0-.011.018-.018.027c-.016 0-.018.009-.026.029a.8.8 0 0 0-.255.614v59.065c0 .497.429.918.942.918");
}

</style>
