<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng7184bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-individual-suite-outline-rounded" /></template>
<style>
.ng7184bqs {
  fill: currentColor;
  d: path("M20.962 16H3.039q-.441 0-.74-.299T2 14.961V8.5q0-.213.143-.357T2.5 8t.357.143T3 8.5V15h8.5V9.039q0-.441.299-.74t.74-.299H19q1.246 0 2.123.877T22 11v3.962q0 .44-.299.739t-.74.299M12.5 15H21v-4q0-.825-.587-1.412T19 9h-6.5zm0-6v6zm-4 3.5q.616-.615.616-1.5T8.5 9.5T7 8.885T5.5 9.5T4.885 11t.615 1.5t1.5.616t1.5-.616m-2.29-.71q-.326-.326-.326-.79t.326-.79t.79-.325t.79.326t.326.789t-.326.79t-.79.326t-.79-.326M7 11");
}

</style>
