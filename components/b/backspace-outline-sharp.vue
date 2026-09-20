<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjebf8bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backspace-outline-sharp" /></template>
<style>
.jjebf8bug {
  fill: currentColor;
  d: path("m11.054 15.308l2.6-2.6l2.6 2.6l.707-.708l-2.6-2.6l2.6-2.6l-.707-.708l-2.6 2.6l-2.6-2.6l-.708.708l2.6 2.6l-2.6 2.6zM8.366 19L3 12l5.366-7H21v14zM4.25 12l4.616 6H20V6H8.866zm7.885 0");
}

</style>
