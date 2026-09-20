<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi4f2zs8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-parking-sharp" /></template>
<style>
.pi4f2zs8i {
  fill: currentColor;
  d: path("M7 20V4h6q2.058 0 3.529 1.471T18 9t-1.471 3.529T13 14H9v6zm2-8h4.046q1.229 0 2.115-.886q.885-.885.885-2.114t-.885-2.114Q14.275 6 13.046 6H9z");
}

</style>
