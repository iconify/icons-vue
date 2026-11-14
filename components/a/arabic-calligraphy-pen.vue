<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3zprjb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arabic-calligraphy-pen" /></template>
<style>
.n3zprjb1y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.092 4.031q-.659-.66-1.591-.66t-1.591.66l-8.767 8.767q-.259.258-.422.585L5.58 15.665q-.565 1.13.276 2.073t2.028.512l2.56-.931q.469-.171.822-.524l8.704-8.704q.66-.659.66-1.591t-.66-1.591zm-3.035 11.467Q18.5 18.212 18.5 19.75q0 3-3 3t-3-3q0-1.538 2.443-4.252q.099-.111.234-.175t.284-.072t.289.042q.141.05.252.15q.029.026.055.055");
}

</style>
