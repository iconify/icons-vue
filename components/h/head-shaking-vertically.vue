<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ez_a0yb5j.css';
import '../../css/r/r4mcw20-b.css';
import '../../css/f/f62cwpbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ez_a0yb5j"/><path clip-rule="evenodd" class="r4mcw20-b"/><path class="f62cwpbfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:head-shaking-vertically" /></template>
