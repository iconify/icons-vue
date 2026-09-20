<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrnj6967m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-outline-rounded" /></template>
<style>
.qrnj6967m {
  fill: currentColor;
  d: path("M8.539 19.192v-5H5.325q-.379 0-.55-.348t.09-.646L11.399 5.7q.243-.279.602-.279t.602.279l6.533 7.498q.261.298.09.646t-.55.348h-3.213v5q0 .344-.233.576t-.575.232H9.346q-.343 0-.575-.232t-.233-.576m1-.192h4.923v-5q0-.348.233-.578q.232-.23.575-.23h2.544L12 6.535l-5.813 6.657H8.73q.343 0 .575.233T9.54 14zM12 13.192");
}

</style>
