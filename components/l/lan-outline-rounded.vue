<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3lc5usmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lan-outline-rounded" /></template>
<style>
.a3lc5usmj {
  fill: currentColor;
  d: path("M3.5 20.462v-3.924q0-.44.299-.739t.74-.299H6.5v-2.384q0-.672.472-1.144t1.144-.472H11.5v-3H9.539q-.441 0-.74-.299t-.299-.74V3.539q0-.44.299-.739t.74-.299h4.923q.44 0 .739.299t.299.74v3.923q0 .44-.299.739t-.74.299H12.5v3h3.385q.67 0 1.143.472q.472.472.472 1.144V15.5h1.962q.44 0 .739.299t.299.74v3.922q0 .441-.299.74t-.74.299H14.54q-.441 0-.74-.299t-.299-.74V16.54q0-.441.299-.74t.74-.299h1.96v-2.384q0-.27-.173-.443t-.442-.173h-7.77q-.269 0-.442.173t-.173.443V15.5h1.962q.44 0 .739.299t.299.74v3.922q0 .441-.299.74t-.74.299H4.54q-.441 0-.74-.299t-.299-.74M9.5 7.5h5v-4h-5zm-5 13h5v-4h-5zm10 0h5v-4h-5zm0-4");
}

</style>
