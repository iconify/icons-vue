<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tw12jkkqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-32-regular" /></template>
<style>
.tw12jkkqj {
  fill: currentColor;
  d: path("M28.583 24C29.918 24 31 25.103 31 26.438c0 2.023-1.714 4.062-6 4.062s-6-2.031-6-4.062C19 25.103 20.082 24 21.417 24zM13.745 2.624a4.5 4.5 0 0 1 4.51 0l.534.309l.002-.001l10.286 5.957a1.852 1.852 0 0 1-.05 3.233l-3.533 1.901a5 5 0 0 0-4.919 2.649l-4.101 2.21a1 1 0 0 1-.948 0L4 12.676V22.5A2.5 2.5 0 0 0 6.5 25h11.273a3.9 3.9 0 0 0-.273 1.436q0 .284.031.564H6.5A4.5 4.5 0 0 1 2 22.5V12.018a4.5 4.5 0 0 1 2.245-3.893zM25 15.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M17.253 4.355a2.5 2.5 0 0 0-2.506 0l-9.5 5.5a2.5 2.5 0 0 0-.826.776l11.578 6.233l11.846-6.379L20 5.942v.003z");
}

</style>
