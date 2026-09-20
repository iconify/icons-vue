<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ri4t-1baq"/><path class="c1wh6t4cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-zig" /></template>
<style>
.c1wh6t4cp {
  fill: var(--svg-color--f7a41d, #f7a41d);
  d: path("m26.875 6.707l-6.362 1.824H9.467v3.733h7.38L5.115 25.293l6.382-1.829h11.036v-3.733h-7.385z");
}

.ri4t-1baq {
  fill: var(--svg-color--f7a41d, #f7a41d);
  d: path("M5.733 19.731v-7.467h2.8V8.531H2v14.933h3.547l3.36-3.733zm20.72-11.2l-3.36 3.733h3.174v7.467h-2.8v3.733H30V8.531z");
}

</style>
