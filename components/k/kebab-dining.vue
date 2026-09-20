<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95k-cu3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kebab-dining" /></template>
<style>
.v95k-cu3l {
  fill: currentColor;
  d: path("M6.942 22.616v-4.5H5.885q-.84 0-1.42-.58t-.58-1.42t.58-1.42t1.42-.58h1.057V12.5H3.885v-4h3.057V6.884H5.885q-.84 0-1.42-.579q-.58-.58-.58-1.42t.58-1.42t1.42-.58h1.057v-1.5h.885v1.5h1.058q.84 0 1.42.58t.58 1.419t-.58 1.42t-1.42.58H7.827V8.5h3.058v4H7.826v1.616h1.057q.84 0 1.42.579q.58.58.58 1.42t-.58 1.42t-1.42.58H7.827v4.5zm9.231 0v-4.5h-1.057q-.84 0-1.42-.58t-.58-1.42t.58-1.42t1.42-.58h1.057V12.5h-3.057v-4h3.057V6.884h-1.057q-.84 0-1.42-.579q-.58-.58-.58-1.42t.58-1.42t1.42-.58h1.057v-1.5h.885v1.5h1.058q.84 0 1.42.58t.58 1.419t-.58 1.42t-1.42.58h-1.058V8.5h3.058v4h-3.058v1.616h1.057q.84 0 1.42.579q.58.58.58 1.42t-.58 1.42t-1.42.58h-1.057v4.5z");
}

</style>
