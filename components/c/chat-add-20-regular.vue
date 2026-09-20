<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wo44pkm7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-add-20-regular" /></template>
<style>
.wo44pkm7m {
  fill: currentColor;
  d: path("M6.5 9.5a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3a.5.5 0 0 0-1 0v3zM18 10a8 8 0 1 0-16 0l.007.346l.026.382a8 8 0 0 0 .829 2.887l.063.12l-.91 3.644l-.014.083v.082a.5.5 0 0 0 .62.441l3.645-.91l.12.064A8 8 0 0 0 18 10M3 10a7 7 0 1 1 3.577 6.108l-.087-.039l-.091-.021a.5.5 0 0 0-.188.01l-3.024.754l.756-3.02l.014-.095a.5.5 0 0 0-.063-.272A6.97 6.97 0 0 1 3 10");
}

</style>
