<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vohiwacya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-4-bar-outline-rounded" /></template>
<style>
.vohiwacya {
  fill: currentColor;
  d: path("M1.5 18.5v-5q0-.625.438-1.062T3 12t1.063.438T4.5 13.5v5q0 .625-.437 1.063T3 20t-1.062-.437T1.5 18.5m6 0V11q0-.625.438-1.062T9 9.5t1.063.438T10.5 11v7.5q0 .625-.437 1.063T9 20t-1.062-.437T7.5 18.5m6 0v-10q0-.625.438-1.062T15 7t1.063.438T16.5 8.5v10q0 .625-.437 1.063T15 20t-1.062-.437T13.5 18.5m6 0v-13q0-.625.438-1.062T21 4t1.063.438T22.5 5.5v13q0 .625-.437 1.063T21 20t-1.062-.437T19.5 18.5");
}

</style>
