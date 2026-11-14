<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7dm4qdty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloon-heart" /></template>
<style>
.y7dm4qdty {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.27 15.458Q3.75 11.342 3.75 7q0-1.998 1.376-3.374T8.5 2.25q2.161 0 3.5 1.487q1.339-1.487 3.5-1.487q1.998 0 3.374 1.376T20.25 7q0 4.33-7.477 8.434q.074.743.386 1.776q.742 2.46.053 4.527q-.024.07-.06.134q-.037.065-.085.12q-.049.056-.107.101q-.059.046-.125.079t-.137.052q-.071.02-.145.025t-.147-.004t-.143-.032q-.142-.048-.254-.145q-.113-.098-.18-.232q-.067-.133-.077-.282q-.011-.149.036-.29q.539-1.616-.065-3.62q-.377-1.248-.453-2.185");
}

</style>
