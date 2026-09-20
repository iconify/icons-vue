<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4unuob5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backpack-sharp" /></template>
<style>
.v4unuob5s {
  fill: currentColor;
  d: path("M5 21V8.399q0-1.26.85-2.214T8 5.054V3h2v2h4V3h2v2.054q1.3.177 2.15 1.129t.85 2.22V21zm10.116-5.423h1v-2.923H7.885v1h7.23z");
}

</style>
