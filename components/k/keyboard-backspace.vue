<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb79ibcrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-backspace" /></template>
<style>
.lb79ibcrw {
  fill: currentColor;
  d: path("M9.308 17.308L4 12l5.308-5.308l.708.708l-4.1 4.1H20v1H5.916l4.1 4.1z");
}

</style>
