<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuln6gb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-off-outline" /></template>
<style>
.kuln6gb3r {
  fill: currentColor;
  d: path("m19.41 20.83l-.87-.868q-.096.019-.173.029q-.076.009-.173.009H5.616q-.672 0-1.144-.472T4 18.385V5.804q0-.095.01-.172t.048-.154l-.889-.895l.708-.707l16.246 16.246zM5.616 19h11.963L5 6.421v11.964q0 .269.173.442t.443.173M20 17.175l-1-1V8.154h-8.021L6.825 4h11.56q.67 0 1.143.472q.472.472.472 1.144z");
}

</style>
