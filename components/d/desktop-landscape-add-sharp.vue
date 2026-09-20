<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlk7f5dzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-landscape-add-sharp" /></template>
<style>
.hlk7f5dzk {
  fill: currentColor;
  d: path("M2 20V4h20v8.775q-.65-.375-1.412-.575t-1.563-.2q-.275 0-.525.013t-.5.062V8H9v1.5h7.5v3.05q-.425.2-.788.438t-.712.537V11H6v5h7.35q-.175.475-.262.988T13 18.025t.075 1.013t.25.962zm16 2v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
