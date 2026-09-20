<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d3owh3b3e.css';
import '../../css/i/i_jkyym3k.css';
import '../../css/q/qkseeyfad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d3owh3b3e"/><path class="i_jkyym3k"/><path class="qkseeyfad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-copy" /></template>
