<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cl_olhb2h.css';
import '../../css/m/m1ql1op8y.css';
import '../../css/i/iu-kfw6gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cl_olhb2h"/><path class="m1ql1op8y"/><path class="iu-kfw6gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:cloud-with-lightning-and-rain" /></template>
