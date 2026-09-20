<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-rrk03j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-arrow-up-outline-sharp" /></template>
<style>
.m1-rrk03j {
  fill: currentColor;
  d: path("M18.885 19V6.916L17.4 8.4l-.708-.708L19.385 5l2.692 2.692l-.713.708l-1.48-1.479V19zM4 17.116v-3.21l7.375-7.273q.485-.466 1.159-.46t1.133.49l.931.943q.46.479.457 1.15t-.482 1.13l-7.325 7.23zm1-1h1.846l4.896-4.839l-.913-.904l-.914-.904L5 14.308zm7.456-5.552l-1.827-1.808z");
}

</style>
