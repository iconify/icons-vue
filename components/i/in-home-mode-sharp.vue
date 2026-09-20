<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9s2vurcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:in-home-mode-sharp" /></template>
<style>
.g9s2vurcx {
  fill: currentColor;
  d: path("m14.637 21l-3.533-3.538l.708-.714l2.825 2.825l5.675-5.65l.688.714zM5 19V9.452l-2.396 1.779l-.598-.787L12 3l10.02 7.439l-.604.792l-1.033-.754l-5.747 5.733l-2.825-2.844l-4.12 4.146L9.172 19z");
}

</style>
