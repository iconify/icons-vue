<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr1ftv-ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paragraph-outline-rounded" /></template>
<style>
.mr1ftv-ed {
  fill: currentColor;
  d: path("M10.49 18.856q-.144-.144-.144-.356V13h-.192q-1.671 0-2.836-1.164Q6.154 10.67 6.154 9t1.164-2.835T10.154 5h5.923q.213 0 .356.144t.144.357t-.144.356t-.356.143h-1.5v12.5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356V6h-2.23v12.5q0 .213-.145.356t-.356.144t-.356-.144");
}

</style>
