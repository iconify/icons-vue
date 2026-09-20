<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2qudgb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:2k-plus-sharp" /></template>
<style>
.c2qudgb9q {
  fill: currentColor;
  d: path("M16.73 13.885h.77v-1.5H19v-.77h-1.5v-1.5h-.77v1.5h-1.5v.77h1.5zm-5.21.807h.884v-2.365l2.288 2.365h1.212l-2.635-2.73l2.635-2.654H14.73l-2.327 2.327V9.308h-.885zm-5.135 0h3.769v-.884H7.269v-1.423h2.885V9.308h-3.77v.884H9.27v1.424H6.385zM4 20V4h16v16z");
}

</style>
