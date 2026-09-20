<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxtbx1lla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:books-movies-and-music-outline" /></template>
<style>
.bxtbx1lla {
  fill: currentColor;
  d: path("M4.77 21q-.33 0-.55-.22T4 20.23V7.82q0-.318.14-.542t.433-.316l8.366-2.577q.346-.104.627.118q.28.222.28.574V7h1.385q.329 0 .549.22t.22.55v2.884h-1V8H5v12h6.598l1 1zM7.691 7h5.154V5.489zm6.165 12.49q-1.165-1.165-1.165-2.836t1.165-2.836t2.835-1.164t2.836 1.164t1.164 2.836t-1.164 2.835t-2.836 1.165q-1.67 0-2.835-1.165m1.97-.95l2.73-1.924l-2.73-1.923zM5 20V8z");
}

</style>
