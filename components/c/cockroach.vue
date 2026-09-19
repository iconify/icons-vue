<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r9jlpx69u.css';
import '../../css/z/zy4jvvbgc.css';
import '../../css/f/f-nz8pbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="r9jlpx69u"/><path class="zy4jvvbgc"/><path class="f-nz8pbmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:cockroach" /></template>
