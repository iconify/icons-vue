<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h7xp58boj"/><path class="ovnlibcwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dune" /></template>
<style>
.h7xp58boj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.425 16.478c-.001 6.063-4.916 10.978-10.979 10.979c-6.062-.002-10.976-4.916-10.978-10.98c.002-6.06 4.916-10.974 10.978-10.977c6.063.001 10.978 4.915 10.98 10.978");
}

.ovnlibcwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.092 27.305c3.102 4.504 5.821 8.842 10.865 12.779c-2.415-2.353-3.31-4.024-4.174-5.866m-3.82-6.691c4.053 5.218 8.014 10.739 14.066 13.831m-8.623-10.954C28.623 38.4 34.389 41.855 41.532 42.5c-7.115-2.104-11.254-9.358-14.22-15.142m6.371 7.69a14 14 0 0 0 4.477 2.011c-6.212-3.424-7.827-8.599-11.113-15.131m4.544 5.858c1.532 1.588 3.411 3.155 5.755 4.446c-3.932-3.542-6.335-8.347-9.22-12.906");
}

</style>
