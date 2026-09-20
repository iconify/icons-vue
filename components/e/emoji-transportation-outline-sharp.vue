<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ej6cb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emoji-transportation-outline-sharp" /></template>
<style>
.a6ej6cb6e {
  fill: currentColor;
  d: path("M10.116 20.616V14.65l1.459-4.15h7.858l1.452 4.15v5.966h-1v-1.693h-8.77v1.693zm1.23-6.77h8.308l-.854-2.461h-6.6zm-.346.885v3.308zm2.203 2.203q.259-.259.259-.626t-.259-.626t-.626-.259t-.626.259t-.259.626t.259.626t.626.258t.626-.258m5.846 0q.259-.259.259-.626t-.259-.626t-.626-.259t-.626.259t-.259.626t.259.626t.626.258t.626-.258M6.346 12.616v-1.539h1.539v1.539zm4-5V6.077h1.539v1.539zm-4 9v-1.539h1.539v1.539zm0 4v-1.539h1.539v1.539zm-3.23 0V7.846h4v-5h8V8.27h-1V3.846h-6v5h-4v11.77zM11 18.038h9v-3.307h-9z");
}

</style>
