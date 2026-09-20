<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpgcenbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flare-outline" /></template>
<style>
.bpgcenbqo {
  fill: currentColor;
  d: path("M2.23 12.5v-1h5v1zm6.02-3.542L6.458 7.166l.707-.708L8.958 8.25zM11.5 7.23v-5h1v5zm4.25 1.727l-.708-.708l1.793-1.792l.707.707zm1.02 3.542v-1h5v1zm-6.193.923Q10 12.846 10 12t.577-1.423T12 10t1.423.577T14 12t-.577 1.423T12 14t-1.423-.577m6.258 4.12l-1.793-1.793l.708-.708l1.792 1.793zm-9.67 0l-.707-.708l1.792-1.793l.708.708zm4.335 4.226v-5h1v5z");
}

</style>
