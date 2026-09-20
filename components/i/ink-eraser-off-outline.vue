<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6lysib6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-eraser-off-outline" /></template>
<style>
.t6lysib6m {
  fill: currentColor;
  d: path("m19.833 21.26l-5.11-5.11L11.962 19H4.558l-1.414-1.413q-.478-.48-.491-1.137t.466-1.161l5.277-5.466l-5.655-5.656l.713-.713l17.092 17.092zM4.985 18h6.55l2.475-2.564l-4.925-4.925l-5.258 5.447q-.154.173-.154.451q0 .28.154.433zm11.832-3.994l-.713-.714l2.838-2.9q.154-.154.154-.442t-.154-.442l-4.084-4.085q-.154-.154-.433-.154t-.433.173l-2.819 2.92l-.707-.708l2.807-2.92q.479-.503 1.134-.494t1.134.489l4.09 4.09q.479.479.488 1.146q.01.668-.469 1.147zM11.56 12.96");
}

</style>
