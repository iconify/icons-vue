<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s62imn-uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emoji-people-outline-sharp" /></template>
<style>
.s62imn-uo {
  fill: currentColor;
  d: path("M9.808 21.5V8.333q-1.871-.35-3.1-1.792q-1.227-1.441-1.4-3.349h1Q6.5 4.998 7.78 6.211t2.97 1.212h2.5q.577 0 .977.17t.81.578l4.236 4.237l-.707.708l-4.374-4.374V21.5h-1v-5.884h-2.384V21.5zm.991-16.222q-.491-.492-.491-1.201t.491-1.201T12 2.385t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491t-1.201-.491");
}

</style>
