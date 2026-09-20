<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rdz_vtbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-page-bottom-left-20-filled" /></template>
<style>
.rdz_vtbcr {
  fill: currentColor;
  d: path("m7.247 14.498l.22-1.5h1.239l-.22 1.5zM14.5 18a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 14.5 2h-9A1.5 1.5 0 0 0 4 3.5v13A1.5 1.5 0 0 0 5.5 18zm-4.572-6.444l-.065.442h.637a.5.5 0 0 1 0 1h-.784l-.22 1.5H10a.5.5 0 0 1 0 1h-.65l-.157 1.074a.5.5 0 0 1-.99-.145l.137-.93H7.1l-.157 1.075a.5.5 0 0 1-.99-.145l.137-.93H5.5a.5.5 0 0 1 0-1h.736l.22-1.5H6a.5.5 0 0 1 0-1h.602l.086-.586a.5.5 0 0 1 .99.145l-.065.442h1.24l.085-.587a.5.5 0 0 1 .99.145");
}

</style>
