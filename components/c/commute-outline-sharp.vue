<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4c44lrkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:commute-outline-sharp" /></template>
<style>
.o4c44lrkg {
  fill: currentColor;
  d: path("M11.673 18.039v1.692h-1v-5.966l1.46-4.15h7.858l1.451 4.15v5.966h-1v-1.693zm.23-5.078h8.309l-.854-2.461h-6.6zm-.345.885v3.308zm1.577 2.462q.376 0 .63-.259q.254-.258.254-.626q0-.367-.254-.626q-.254-.258-.63-.258t-.63.258q-.255.259-.255.626q0 .368.254.626q.255.259.63.259m5.847 0q.376 0 .63-.259q.255-.258.255-.626q0-.367-.255-.626q-.254-.258-.63-.258t-.63.258t-.255.626t.255.626q.254.259.63.259M4.558 19.5v-.308L6.25 17.5q-1.404 0-2.548-.615Q2.558 16.269 2.558 15V6.5q0-1.016 1.494-1.508T8.558 4.5q3.046 0 4.523.487T14.558 6.5v1.346h-1V6.5h-10v7h5.346v6zm1.126-3.87q.258-.254.258-.63t-.258-.63t-.626-.254t-.626.254t-.259.63t.259.63t.626.254t.626-.254m5.874 1.524h9v-3.308h-9z");
}

</style>
