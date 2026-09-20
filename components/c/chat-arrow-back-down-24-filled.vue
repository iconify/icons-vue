<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4z_9py_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-arrow-back-down-24-filled" /></template>
<style>
.e4z_9py_f {
  fill: currentColor;
  d: path("M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 1.643.397 3.23 1.145 4.65l-1.116 4.29a.85.85 0 0 0 1.036 1.036l4.29-1.117a9.96 9.96 0 0 0 5.426 1.112a6.5 6.5 0 0 1 9.19-9.19q.029-.385.029-.78m1 5.5a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0m-6.646 2.146a.5.5 0 0 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.708l1.5-1.5a.5.5 0 0 1 .708.708l-.647.646h2.043A2.25 2.25 0 0 0 20 15.75v-.25a.5.5 0 0 1 1 0v.25A3.25 3.25 0 0 1 17.75 19h-2.043z");
}

</style>
