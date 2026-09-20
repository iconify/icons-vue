<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfsi9rbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-off-outline-sharp" /></template>
<style>
.zfsi9rbrb {
  fill: currentColor;
  d: path("m19.41 20.83l-.831-.83H4V5.421l-.83-.836l.707-.708l16.246 16.246zM5 19h12.579L5 6.421zm15-1.825l-1-1V8.154h-8.021L6.825 4H20z");
}

</style>
