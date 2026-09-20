<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8zpe9b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-square-sharp" /></template>
<style>
.i8zpe9b9s {
  fill: currentColor;
  d: path("M10 14v-2.615l9.683-9.683l2.56 2.564L12.518 14zm9.466-8.354l1.347-1.361l-1.111-1.17l-1.387 1.381zM4 20V4h10.002l-6.386 6.387v5.998h5.896L20 9.895V20z");
}

</style>
