<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ecxgx1b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-off-20-filled" /></template>
<style>
.ecxgx1b6z {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L5.793 6.5H3.75a.75.75 0 0 0 0 1.5h3.543l3.5 3.5H3.75a.75.75 0 0 0 0 1.5h8.543l4.853 4.854a.5.5 0 0 0 .708-.708zM13.62 11.5l1.5 1.5h1.129a.75.75 0 0 0 0-1.5zm-5-5l1.5 1.5h6.129a.75.75 0 0 0 0-1.5z");
}

</style>
