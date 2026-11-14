<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j97nykzjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-budget" /></template>
<style>
.j97nykzjb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 17.25q-.104 0-.205-.029q-3.403-.966-3.624-4.497q-.21-3.358 2.724-4.773q1.428-3.949 5.706-4.338q4.312-.392 6.428 3.295q3.427 1.492 3.215 5.314q-.026.47-.103.899Q19.595 13 19 13h-2q-2.071 0-3.536 1.464q-1.191 1.192-1.413 2.786zm11-3q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906m-4.931-.811q.211-.162.561-.185q-.27.101-.561.185");
}

</style>
