<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjz120bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-remove" /></template>
<style>
.rjz120bdd {
  fill: currentColor;
  d: path("M21 7h-6V5h6zM5 21V5q0-.825.588-1.412T7 3h7q-.5.75-.75 1.438T13 6q0 1.8 1.138 3.175T17 10.9q.575.075 1 .075t1-.075V21l-7-3z");
}

</style>
