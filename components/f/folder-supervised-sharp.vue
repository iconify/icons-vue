<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiflyyb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-supervised-sharp" /></template>
<style>
.fiflyyb7w {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v3.91q-.76-.452-1.602-.681T17.668 10q-2.797 0-4.646 1.947t-1.849 4.567q0 .646.127 1.261T11.68 19zm11.385 0v-.165q0-.876.869-1.355t2.438-.48t2.439.48t.869 1.355V19zm2.241-4.049q-.434-.434-.434-1.066t.434-1.067t1.066-.433t1.067.433t.433 1.067t-.433 1.066t-1.067.434t-1.066-.434");
}

</style>
