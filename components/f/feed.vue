<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uz9gb9bqr.css';
import '../../css/o/o_mo92p9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><circle class="uz9gb9bqr"/><path class="o_mo92p9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:feed" /></template>
