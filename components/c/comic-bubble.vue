<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm0qwqbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comic-bubble" /></template>
<style>
.pm0qwqbfx {
  fill: currentColor;
  d: path("m11 19.477l-2.483-2.483h-3.51v-3.51L2.522 11l2.483-2.483v-3.51h3.51L11 2.522l2.483 2.483h3.51v3.51L19.478 11l-2.708 2.708l2.087 4.073q.136.267.08.503q-.055.235-.236.416t-.416.237q-.236.055-.503-.081l-4.073-2.087z");
}

</style>
