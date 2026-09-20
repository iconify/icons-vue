<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sgilrxuaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-starburst-20-filled" /></template>
<style>
.sgilrxuaw {
  fill: currentColor;
  d: path("M11.54 1.898a2.42 2.42 0 0 1 3.103 1.285l.424.976c.151.347.43.625.777.776l.975.425a2.417 2.417 0 0 1 1.285 3.101l-.39.99a1.5 1.5 0 0 0 0 1.1l.39.989a2.42 2.42 0 0 1-1.285 3.102l-.975.424a1.5 1.5 0 0 0-.777.777l-.424.975a2.42 2.42 0 0 1-3.102 1.285l-.99-.39a1.5 1.5 0 0 0-1.098 0l-.99.39a2.417 2.417 0 0 1-3.102-1.285l-.425-.975a1.5 1.5 0 0 0-.776-.777l-.976-.424A2.42 2.42 0 0 1 1.9 11.54l.39-.99a1.5 1.5 0 0 0 0-1.098l-.39-.99A2.417 2.417 0 0 1 3.184 5.36l.976-.425a1.5 1.5 0 0 0 .776-.776l.425-.976a2.417 2.417 0 0 1 3.101-1.285l.99.39c.354.138.746.139 1.1 0zm1.814 5.75a.5.5 0 0 0-.707 0l-3.646 3.646l-1.647-1.647a.5.5 0 1 0-.707.707l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.707");
}

</style>
