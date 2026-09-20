<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="exf3bg3rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drink-to-go-20-regular" /></template>
<style>
.exf3bg3rf {
  fill: currentColor;
  d: path("M13.853 2.146a.5.5 0 0 1 0 .708L12.706 4h1.624a.75.75 0 0 1 .704.492l.917 2.5A.75.75 0 0 1 15.247 8h-.339l-1.425 8.337A2 2 0 0 1 11.512 18H8.487a2 2 0 0 1-1.972-1.663L5.09 8h-.34a.75.75 0 0 1-.703-1.01l.923-2.5A.75.75 0 0 1 5.674 4h5.642a.5.5 0 0 1 .08-.104l1.75-1.75a.5.5 0 0 1 .707 0M6.105 8L7.5 16.169a1 1 0 0 0 .986.831h3.025a1 1 0 0 0 .985-.831L13.894 8zm-.996-1h9.78l-.734-2H5.848z");
}

</style>
