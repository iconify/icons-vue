<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kds1gyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-awning" /></template>
<style>
.d4kds1gyn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5v3q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.438q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h1.626q-.188.531-.188 1.25q0 2.75 2.75 2.75T15 16.5q0-.987-.354-1.619q.104-.176.104-.381V9.115l6.114 9.782q.039.063.09.117t.111.097t.127.073t.139.047q.072.016.146.019t.147-.01q.073-.012.142-.039q.069-.026.131-.065q.063-.039.117-.09t.097-.111t.073-.127t.047-.139q.016-.072.019-.146t-.01-.147q-.012-.073-.039-.142q-.026-.069-.065-.131l-7.5-12l-.008-.013q-.051-.079-.12-.142t-.151-.108t-.173-.067T14 5.75H8.5q-.095 0-.188.024q-.092.024-.176.07t-.152.112t-.12.147L5.584 9.75H3.5q-1.75 0-1.75 1.75");
}

</style>
