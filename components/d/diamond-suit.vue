<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pz5q1vbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:diamond-suit" /></template>
<style>
.pz5q1vbos {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M18.437 35.747c-.242.337-.632.337-.874 0L5.314 18.612c-.242-.338-.242-.886 0-1.224L17.563.253c.242-.338.632-.338.874 0l12.25 17.135c.241.338.241.886 0 1.224z");
}

</style>
