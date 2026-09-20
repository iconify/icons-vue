<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-ewy-e6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-page-top-left-20-filled" /></template>
<style>
.d-ewy-e6y {
  fill: currentColor;
  d: path("m8.753 5.502l-.22 1.5H7.295l.22-1.5zM5.5 2A1.5 1.5 0 0 0 4 3.5v13A1.5 1.5 0 0 0 5.5 18h9a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 14.5 2zm.572 6.444l.065-.442H5.5a.5.5 0 0 1 0-1h.784l.22-1.5H6a.5.5 0 0 1 0-1h.65l.157-1.074a.5.5 0 0 1 .99.145l-.137.93H8.9l.157-1.075a.5.5 0 0 1 .99.145l-.137.93h.59a.5.5 0 0 1 0 1h-.736l-.22 1.5H10a.5.5 0 0 1 0 1h-.602l-.086.586a.5.5 0 1 1-.99-.145l.065-.442h-1.24l-.085.587a.5.5 0 1 1-.99-.145");
}

</style>
